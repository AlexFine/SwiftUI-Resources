# SwiftUI-Resources
Just a list of good websites, docs, notes, advice, etc. 

## Links
<ul>
  <li> Properly load images from server: https://medium.com/@dmytro.anokhin/url-image-view-in-swiftui-f08f85d942d8  </li>
</ul>


## Notes 
<ul>
  <li> Empty dictionaries can be initialized as <code> let emptyDictionary = \[String: Float\]() </code> and if type can be inferred use <code> dictName = [:] </code> </li> 
  <li> Dictionaries aren't dictionaries ... super weird. They're hash tables. </li>
  <li> For setting values which sometimes exist, but not always, optionals are a great choice. <code> var optionalString: String? = "Faf" </code> </li>
  <li> In situations of multiple optionalities which don't all subscribe to the same condition, use <code> switch </code> instead of <code> if </code> </li>
  
</ul>


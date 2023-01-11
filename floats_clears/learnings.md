1. float takes element out of normal flow of the page.
2. But it takes the space in the flow of page(space does not get filled by upcoming elements)
3. let say a div is there and it is followed by another paragraph or any other div scoped element.
4. Then the following elements will wrap around the floated element (assuming left float is applied).
5. Imagine a news paper headline. on top left their is one image and the news is written right after it in wrapped fashion.
6. padding/margin only gets applied to elements in same flow of page(or atleast i think so)
7. so if we apply margin/ padding to wrapped content it wont get applied

**ISSUES WITH FLOAT**
1. float takes content out of flow. this causes hindrance with normal css (padding, normal width height of parent container etc)
2. clear comes to a little bit rescue. but it just clears the space which would be taken up by other content which would have been ideally wrapped around floated element.
3. display:flow-root is better in those cases when a container which includes floated element and other things and issues related to width height occur
4. overflow auto and display:flow-root are two options to solve issues float. and flow-root is often considered as a better option and modern code

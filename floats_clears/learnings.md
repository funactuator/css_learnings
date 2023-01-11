1. float takes element out of normal flow of the page.
2. But it takes the space in the flow of page(space does not get filled by upcoming elements)
3. let say a div is there and it is followed by another paragraph or any other div scoped element.
4. Then the following elements will wrap around the floated element (assuming left float is applied).
5. Imagine a news paper headline. on top left their is one image and the news is written right after it in wrapped fashion.
6. padding/margin only gets applied to elements in same flow of page(or atleast i think so)
7. so if we apply margin/ padding to wrapped content it wont get applied
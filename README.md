# html_learning
Documenting my learnings of HTML

Learned new concepts from this [course](https://youtu.be/kUMe1FH4CHE) like
1. **Lazy loading** in HTML5 with &lt;img&gt; tag with the `loading` attribute<br>
You can achieve this by just setting the loading attribute to `lazy`

2. Why is it important to have width and height attributes in &lt;img&gt; tag?<br>
The &lt;img&gt; tag reserves the space of the default width and height of the image and allocates the space to the image. But, If you do not provide the width and height of the image specifically, Then if there is any change in the image URL which is causing the issue, The image will not be rendered, But only the text specified in the `alt` attribute is displayed with that specific width and height. This is why it is important to mention specific width and heigth in the &lt;img&gt; tag

3. Importance of having semantic tags<br>
Semantic tags helps in many ways. Some of the notable ones are that It is useful for developers to understand within the code that in which section there is a problem, It is helpful in terms of assistive technology which enables screen readers to go through the semantic tags and help the impaired people to go through the content appropriately

<!-- 
### Exercise 1

1. Create a simple page having a header, main content, and a footer.

2. Inside the header keep the brand name to the left and all the navigation to the right.

3. Inside the main content take an article section having two columns. In the first column put a heading and some introductory text of the article and in the second column take an image. -->
<!DOCTYPE html>
<html>
	<head>
		<title></title>
		<meta charset="utf-8">
		<link rel="stylesheet" type="text/css" href="assets/stylesheet/main.css">
    </head>
<body>
    <header>
     	<h1>Extracts From "Our Cats by Harrison Weir"</h1>
    </header>
    <main>
        <div class="box clearfix">
            <aside class="left">
                <p>Introduction</p>
                <p>The cat show</p>
                <p>Habits</p>
                <p>Trained cats</p>
                <p>Usefulness of cats</p>
            </aside>
            <article class="article">
                <h2>Usefullness of cats</h2>
                <img src="assets/media/cat.jpg" alt="Cat">
                <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum'</p> 
                <p class="para"> a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).</p>
                <p>opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum.</p>                        
            </article>
            <aside class="left">
                <p>Let anyone have the a plauge of rats and mice, as I have once had, and let them to be delivered therefrom by cats, as I was and they will have a lasting and kind regard for them.</p>
            </aside>  
        </div>   
    </main> 
</body>
</html>
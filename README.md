# DESIGN-OF-A-CARD<BR>
IT IS A CARD WHERE I HAVE USED HTML AND CSS ONLY TO MAKE A WONDERFUL CARD.<BR>
SOURCE CODE:-<BR>
<!DOCTYPE html>
<html lang="en">

<head>
    <title>CARD DESIGN</title>
    <meta name="description" content="A responsive card design example with image, context tags, description, and a read more button. Suitable for both mobile and desktop layouts.">
    <meta name="viewport" content="width=device-width, initial-scale=1">
   <style>
        * {
            padding: 0;
            margin: 0;
        }

        .BIGBOX {
            width: 500PX;
            min-height: 500PX;
            background-color: rgb(233, 220, 202);
            border: 5 PX SOLID BLACK;
            padding: 20px;
            margin:50px;
        }

        .innerbox {
            background-color: white;
            width: 80%;
            min-height: 20%;
            /* border: 5px solid yellow; */
            margin: 40px;
            border-radius: 40px;
            display:flex;
            flex-direction: column;
        }

        .image img {
            width: 90%;
            /* height: 40%; */
            margin-left: 10px;
            margin-top: 20px;
            margin-bottom: 20px;
            border-style: double;
            border-color: purple;
            border-width: 10px;
            border-radius: 40px;;
        }

        .context span {
            color: blue;
            text-align: left;
            font-size: 15px;
            border: 1px solid black;
            padding: 3px;
            margin: 20px;

        }

        .context {
            margin-top: 5px;
            border: none;
            border-radius: 20px;

        }
        .context span {
            margin-left: 20px;
            margin-right: 20px;
            padding: 5px;
            font-size: 15px;
            color: white;
            background-color: black;
            border-radius: 20px;
        }
        .description {
            margin-top: 20px;
            /* margin-bottom: 10px; */
        }
        .description H1 {
            margin-bottom:10px;
            margin-left:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            text-decoration:underline dotted
        }
        .description P {
            margin-left: 20px;
            margin-right: 20px;
            font-size: 20px;
            color: black;
        }
        .readbutton{
           display:flex;
           justify-content: center;
           align-items:flex-end;
           margin-top: 20px;
           margin-bottom:20px;
        }
        .readbutton button {
            width: 150px;
            height: 50px;
            background-color: rgb(0, 0, 0);
            color: white;
            font-size: 20px;
            border-radius: 20px;
            border: none;
        }
    </STYLE>
</HEAD>

<BODY>
    <DIV class="BIGBOX">
        <div class="innerbox">
            <div class="image">
                <img src="IMAGE.webp" alt="Image Description">
            </div>
            <div class="context">
                <span>EARTH</span>
                <span>CLOUD</span>


            </div>
            <div class="description">
                <H1>CARD</H1>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus explicabo ab architecto fugiat, doloribus accusamus veniam officia iure voluptate ducimus placeat incidunt et, provident velit atque repudiandae eos cum nesciunt rem itaque. Aliquam maiores vero commodi eius reiciendis doloribus cupiditate, ad quas consectetur quibusdam molestiae dolores optio magnam quasi ullam asperiores. Sint adipisci veritatis incidunt voluptates nostrum magnam ratione quae facere quos perspiciatis velit assumenda, voluptatibus quo soluta recusandae consequatur suscipit, nihil blanditiis tempore, necessitatibus quasi? Non quod voluptate iste excepturi illum, dolores architecto qui veritatis impedit ut deleniti. Dolores modi aperiam praesentium debitis laboriosam voluptas quaerat quisquam obcaecati voluptate.</p>
            </div>
            <div class="readbutton">
                <button>READ MORE</button>

        </div>
    </DIV>
</BODY>

</html>

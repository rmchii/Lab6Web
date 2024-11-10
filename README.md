# Lab6Web

jQuery Framework
<!DOCTYPE html>
<html>
<head>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
    <script>
        $(document).ready(function() {
            $("#flip").click(function() {
                $("#panel").slideToggle("slow");
            });
        });
    </script>
    <style type="text/css">
        #panel, #flip {
            padding: 5px;
            text-align: center;
            background-color: #e5eecc;
            border: solid 1px #c3c3c3;
        }
        #panel {
            padding: 50px;
            display: none;
        }
    </style>
</head>
<body>
    <div id="flip">Click to slide the panel down or up</div>
    <div id="panel">Hello world!</div>
</body>
</html>


![Screenshot (367)](https://github.com/user-attachments/assets/26d2dc34-235f-49ee-8921-e27e16991022)

Animation
<!DOCTYPE html>
<html>
<head>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
    <script>
        $(document).ready(function(){
            $("button").click(function(){
                var div = $("div");
                div.animate({height: '300px', opacity: '0.4'}, "slow");
                div.animate({width: '300px', opacity: '0.8'}, "slow");
                div.animate({height: '100px', opacity: '0.4'}, "slow");
                div.animate({width: '100px', opacity: '0.8'}, "slow");
            });
        });
    </script>
</head>
<body>
    <button>Start Animation</button>
    <div style="background:#98bf21;height:100px;width:100px;position:absolute;"></div>
</body>
</html>


![Screenshot (369)](https://github.com/user-attachments/assets/ce2c0e2a-8212-4819-ae0b-ea8eb4b020ed)

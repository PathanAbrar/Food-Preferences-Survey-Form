<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Preferences Survey Form</title>
    <style>
        body {
            font-family: sans-serif;  
            }
        th, 
        td{
            padding: 10px;
        }
        label{
            margin-right: 20px;
        }
        button{
            margin: 2px;
        }
    </style>
</head>
<body >
    <h1>Food Preferences - Survey Form</h1>
    <h5>please fill out and submit the survery form at the earliest </h5>
<hr />
<form action="" method="post">
    <table>

    <tr>
        <td> 1. Name</td>
        <td><input type="text" name="user"></td>
    </tr>
    <tr>
        <td>2. Age</td>
        <td> <input type="number" name="age" min="13" max="100"></td>
    </tr>
    <tr>
        <td>3. where do you eat most often</td>
        <td> 
            <input type="radio" name="home" id="location" value="home">
            <label for="home">at home</label>

            <input type="radio" name="work_or_school" id="location" value="work_or_school">
            <label for="work_or_school">at work/school</label>
        
            <input type="radio" name="restaurant" id="location" value="restaurant">
            <label for="restaurant">at a restaurant</label>
        </td>
    </tr>
    <tr>
            <td colspan="2">4. specify how often</td>  
    </tr>
    <tr>
         <td colspan="2">
            <table style="font-size: 0.7em; border: 1px solid;">
                <thead>
                <tr>
                    <th></th>
                    <th >every day</th>
                    <th>a few times a weak</th>
                    <th>once a weak</th>
                    <th>several times a month</th>
                    <th>once a month</th>
                    <th>less often than once a month</th>
                </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>you prepare your own meals</td>
                        <td style="text-align: center;"><input type="radio" name="you_prepare" value="every day"></td>
                        <td style="text-align: center;"><input type="radio" name="you_prepare" value="a few times a weak"></td>
                        <td style="text-align: center;"><input type="radio" name="you_prepare" value="once a weak"></td>
                        <td style="text-align: center;"><input type="radio" name="you_prepare" value="several times a month"></td>
                        <td style="text-align: center;"><input type="radio" name="you_prepare" value="once a month"></td>
                        <td style="text-align: center;"><input type="radio" name="you_prepare" value="less often than once a month"></td>  
                    </tr>
                    
                    <tr >
                        <td>You eat out</td>
                        <td style="text-align: center;"><input type="radio" name="You_eat_out" value="every day"></td>
                        <td style="text-align: center;"><input type="radio" name="You_eat_out" value="a few times a weak"></td>
                        <td style="text-align: center;"><input type="radio" name="You_eat_out" value="once a weak"></td>
                        <td style="text-align: center;"><input type="radio" name="You_eat_out" value="several times a month"></td>
                        <td style="text-align: center;"><input type="radio" name="You_eat_out" value="once a month"></td>
                        <td style="text-align: center;"><input type="radio" name="You_eat_out" value="less often than once a month"></td>  
                    </tr> 

                    <tr >
                        <td>You order food for home</td>
                        <td style="text-align: center;"><input type="radio" name="You_order_food" value="every day"></td>
                        <td style="text-align: center;"><input type="radio" name="You_order_food" value="a few times a weak"></td>
                        <td style="text-align: center;"><input type="radio" name="You_order_food" value="once a weak"></td>
                        <td style="text-align: center;"><input type="radio" name="You_order_food" value="several times a month"></td>
                        <td style="text-align: center;"><input type="radio" name="You_order_food" value="once a month"></td>
                        <td style="text-align: center;"><input type="radio" name="You_order_food" value="less often than once a month"></td>  
                    </tr>

                </tbody>
                </table>
            </td>
        </tr>

        
   

    <tr>
        <td>5. The most common places you visit are restaurants serving food of origin:</td>
    </tr>
    <tr>
        <td colspan="2">
            <table>
                <tr>
                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Polish"> 
                        <label for="Polish">Polish</label>
                    </td>

                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Indian"> 
                        <label for="Indian">Indian</label>
                    </td>  
                </tr>

                <tr>
                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Italian"> 
                        <label for="Italian">Italian</label>
                    </td>

                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Spanish"> 
                        <label for="Spanish">Spanish</label>
                    </td>  
                </tr>

                <tr>
                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Asian"> 
                        <label for="Asian">Asian</label>
                    </td>

                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Chinese"> 
                        <label for="Chinese">Chinese</label>
                    </td>  
                </tr>

                <tr>
                    <td>
                        <input type="checkbox" name="food_origin_preference" value="American"> 
                        <label for="American">American</label>
                    </td>

                    <td>
                        <input type="checkbox" name="food_origin_preference" value="Other"> 
                        <label for="Other">Other</label>
                    </td>  
                </tr>

                <tr>
                    <td>6. Goven an option, would you go Vegan?</td>
                    <td>
                        <input type="radio" name="vegan" id="sure" value="sure"> 
                        <label for="sure"> Sure</label>

                        <input type="radio" name="vegan" id="no" value="no"> 
                        <label for="no"> No</label>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <button>Submit</button>
                        <button type="reset">reset</button>
                    </td>
                </tr>
            </table>
        </td>
    </tr>

        

</table>
</form>



</body>
</html>

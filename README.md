<!DOCTYPE html>
<html>
<head>
    <title>Beyond The Limit</title>
</head>
<body>

    
    <h1><strong>BEYOND THE LIMIT</strong></h1>

    
    <img src="https://via.placeholder.com/300x350.png?text=Beyond+The+Limit+T-Shirt" alt="Beyond The Limit T-Shirt">

    
    <h2>Product Information</h2>

    <p><b>Product Name:</b> Beyond The Limit Classic T-Shirt</p>
    <p><b>Price:</b> 450.00</p>
    <p><b>Description:</b> Comfortable cotton T-shirt with the Beyond The Limit logo.</p>

    
    <h3>Size Chart</h3>
    <table border="1">
        <tr>
            <th>Available Sizes</th>
        </tr>
        <tr>
            <td>Small (S)</td>
        </tr>
        <tr>
            <td>Medium (M)</td>
        </tr>
        <tr>
            <td>Large (L)</td>
        </tr>
        <tr>
            <td>Extra Large (XL)</td>
        </tr>
    </table>

    <br>

    
    <button onclick="document.getElementById('popup').style.display='block'">
        Add to Cart
    </button>

    
    <div id="popup" style="display:none; border:1px solid black; padding:10px; margin-top:20px;">
        <h3>Select Your Size</h3>

        <select>
            <option>Small (S)</option>
            <option>Medium (M)</option>
            <option>Large (L)</option>
            <option>Extra Large (XL)</option>
        </select>

        <br><br>

        <button onclick="alert('Thank you for your purchase!')">
            Buy Now
        </button>

        <button onclick="document.getElementById('popup').style.display='none'">
            Close
        </button>
    </div>

</body>
</html>

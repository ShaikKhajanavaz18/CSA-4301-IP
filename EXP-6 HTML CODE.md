
<!DOCTYPE html>
<html>
<head>
    <title>Online Cake Ordering System</title>
</head>
<body>
    <h1>Online Cake Ordering System</h1>
    <hr>

    <h2>User Registration</h2>
    <form>
        Name: <input type="text" required><br><br>
        Email: <input type="email" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Register</button>
    </form>

    <h2>User Login</h2>
    <form>
        Username: <input type="text" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Login</button>
    </form>

    <h2>Search and Filter Cakes</h2>
    <input type="text" placeholder="Search cake name">

    <select>
        <option>All Categories</option>
        <option>Birthday Cake</option>
        <option>Wedding Cake</option>
        <option>Chocolate Cake</option>
        <option>Fruit Cake</option>
    </select>

    <select>
        <option>All Prices</option>
        <option>Below Rs. 500</option>
        <option>Rs. 500 - 1000</option>
        <option>Above Rs. 1000</option>
    </select>
    <button type="button">Search</button>

    <h2>Available Cakes</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Cake Name</th>
            <th>Category</th>
            <th>Price</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>Chocolate Cake</td>
            <td>Birthday</td>
            <td>Rs. 500</td>
            <td>Rich chocolate cream cake</td>
        </tr>
        <tr>
            <td>Black Forest Cake</td>
            <td>Special Occasion</td>
            <td>Rs. 700</td>
            <td>Chocolate and cherry cake</td>
        </tr>
        <tr>
            <td>Vanilla Cake</td>
            <td>Birthday</td>
            <td>Rs. 400</td>
            <td>Soft vanilla cream cake</td>
        </tr>
    </table>

    <h2>Place Order</h2>
    <form>
        Cake Name: <input type="text" required><br><br>
        Size:
        <select>
            <option>Half Kg</option>
            <option>1 Kg</option>
            <option>2 Kg</option>
        </select><br><br>
        Quantity: <input type="number" min="1" value="1"><br><br>
        Custom Message: <input type="text"><br><br>
        Shipping Address: <textarea required></textarea><br><br>
        <button type="button">Add to Cart</button>
        <button type="button">Place Order</button>
    </form>

    <h2>My Orders</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Order ID</th>
            <th>Cake</th>
            <th>Status</th>
        </tr>
        <tr>
            <td>101</td>
            <td>Chocolate Cake</td>
            <td>Out for Delivery</td>
        </tr>
    </table>

    <h2>Update Shipping Address</h2>
    <textarea placeholder="Enter new address"></textarea><br><br>
    <button type="button">Update Address</button>

    <h2>Admin Login</h2>
    <form>
        Username: <input type="text"><br><br>
        Password: <input type="password"><br><br>
        <button type="button">Login</button>
    </form>

    <h2>Admin Management</h2>
    <p>Manage cake products, images, descriptions, prices, and customer orders.</p>
    <button type="button">Update Order Status</button>

    <h2>Logout</h2>
    <button type="button">Logout</button>

    <footer>
        <hr>
        <p>&copy; 2026 Online Cake Ordering System</p>
    </footer>
</body>
</html>

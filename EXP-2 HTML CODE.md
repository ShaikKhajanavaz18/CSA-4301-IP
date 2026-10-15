
<!DOCTYPE html>
<html>
<head>
    <title>Hotel Room Booking</title>
</head>
<body>
    <h1>Online Hotel Room Booking</h1>
    <hr>

    <h2>User Registration</h2>
    <form>
        Name: <input type="text" required><br><br>
        Email: <input type="email" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Register</button>
    </form>

    <h2>Search and Book Rooms</h2>
    <form>
        Destination: <input type="text" required><br><br>
        Check-in: <input type="date" required><br><br>
        Check-out: <input type="date" required><br><br>
        Guests: <input type="number" min="1" required><br><br>
        Room Type:
        <select>
            <option>Single Room</option>
            <option>Double Room</option>
            <option>Deluxe Room</option>
            <option>Suite Room</option>
        </select><br><br>
        <button type="button">Check Availability</button>
        <button type="button">Book Room</button>
    </form>

    <h2>Room Types and Prices</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Room Type</th>
            <th>Price per Night</th>
            <th>Availability</th>
        </tr>
        <tr>
            <td>Single Room</td>
            <td>Rs. 1500</td>
            <td>Available</td>
        </tr>
        <tr>
            <td>Double Room</td>
            <td>Rs. 2500</td>
            <td>Available</td>
        </tr>
        <tr>
            <td>Deluxe Room</td>
            <td>Rs. 3500</td>
            <td>Available</td>
        </tr>
        <tr>
            <td>Suite Room</td>
            <td>Rs. 5000</td>
            <td>Available</td>
        </tr>
    </table>

    <h2>My Booking History</h2>
    <p>Booking ID: 101</p>
    <p>Room Type: Double Room</p>
    <p>Check-in: 20-10-2026</p>
    <p>Check-out: 22-10-2026</p>
    <button type="button">Modify Booking</button>
    <button type="button">Cancel Booking</button>

    <h2>Administrator</h2>
    <form>
        Admin Username: <input type="text"><br><br>
        Password: <input type="password"><br><br>
        <button type="button">Admin Login</button>
    </form>
    <p>Manage room quantities, prices, and customer bookings.</p>

    <h2>About Us</h2>
    <p>We provide comfortable rooms and convenient online booking services.</p>

    <h2>Contact Us</h2>
    <p>Email: hotel@example.com</p>
    <p>Phone: 9876543210</p>

    <h2>Customer Service Q&A</h2>
    <p>Q: Can I cancel my booking?</p>
    <p>A: Yes, up to 3 days before arrival.</p>

    <h2>Local Travel Guide</h2>
    <p>Explore nearby tourist attractions and transportation facilities.</p>

    <h2>Privacy Policy</h2>
    <p>Customer information should be protected and kept confidential.</p>

    <footer>
        <hr>
        <p>&copy; 2026 Hotel Room Booking Website</p>
    </footer>
</body>
</html>

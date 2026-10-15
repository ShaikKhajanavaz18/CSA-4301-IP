
<!DOCTYPE html>
<html>
<head>
    <title>Flight Reservation System</title>
</head>
<body>
    <h1>Online Flight Reservation System</h1>
    <hr>

    <h2>User Registration</h2>
    <form>
        Name: <input type="text" required><br><br>
        Email: <input type="email" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Register</button>
    </form>

    <h2>Administrator Login</h2>
    <form>
        Username: <input type="text"><br><br>
        Password: <input type="password"><br><br>
        <button type="button">Login</button>
        <button type="reset">Reset</button>
    </form>

    <h2>Forgot Password</h2>
    <input type="email" placeholder="Enter registered email">
    <button type="button">Reset Password</button>

    <h2>Search Flight</h2>
    <form>
        From: <input type="text" required><br><br>
        To: <input type="text" required><br><br>
        Travel Date: <input type="date" required><br><br>
        Class:
        <select>
            <option>Economy</option>
            <option>Business</option>
            <option>First Class</option>
        </select><br><br>
        <button type="button">Search Flight</button>
    </form>

    <h2>Available Flights</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Flight No.</th>
            <th>Airline</th>
            <th>Departure</th>
            <th>Seats</th>
            <th>Fare</th>
        </tr>
        <tr>
            <td>AI101</td>
            <td>Air India</td>
            <td>09:00 AM</td>
            <td>Available</td>
            <td>Rs. 4500</td>
        </tr>
        <tr>
            <td>6E202</td>
            <td>IndiGo</td>
            <td>02:00 PM</td>
            <td>Available</td>
            <td>Rs. 3500</td>
        </tr>
    </table>

    <h2>Book Ticket</h2>
    <form>
        Passenger Name: <input type="text" required><br><br>
        Age: <input type="number" min="1" required><br><br>
        Seat Number: <input type="number" min="1" required><br><br>
        <button type="button">Book Ticket</button>
    </form>

    <h2>Ticket Payment</h2>
    <p>Select a payment method:</p>
    <select>
        <option>UPI</option>
        <option>Credit Card</option>
        <option>Debit Card</option>
    </select>
    <button type="button">Pay Now</button>

    <h2>My Ticket / Booking Status</h2>
    Booking ID: <input type="text">
    <button type="button">View Booking</button>
    <button type="button" onclick="window.print()">Print Ticket</button>

    <h2>Cancel Ticket</h2>
    Booking ID: <input type="text">
    <button type="button">Cancel Ticket</button>

    <h2>Customer Feedback</h2>
    <textarea placeholder="Enter your feedback"></textarea><br><br>
    <button type="button">Submit Feedback</button>

    <h2>Admin Report</h2>
    <p>Administrators can manage flights, fares, seats, and reservations.</p>
    <button type="button">Generate Report</button>

    <footer>
        <hr>
        <p>&copy; 2026 Flight Reservation System</p>
    </footer>
</body>
</html>

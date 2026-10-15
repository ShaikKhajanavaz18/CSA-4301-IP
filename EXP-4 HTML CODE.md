
<!DOCTYPE html>
<html>
<head>
    <title>Train Reservation System</title>
</head>
<body>
    <h1>Online Train Reservation System</h1>
    <hr>

    <h2>Passenger Registration</h2>
    <form>
        Name: <input type="text" required><br><br>
        Email: <input type="email" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Register</button>
    </form>

    <h2>Passenger Login</h2>
    <form>
        Username: <input type="text" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Login</button>
    </form>

    <h2>Search Train</h2>
    <form>
        From Station: <input type="text" required><br><br>
        To Station: <input type="text" required><br><br>
        Journey Date: <input type="date" required><br><br>
        Class:
        <select>
            <option>Sleeper</option>
            <option>AC 3 Tier</option>
            <option>AC 2 Tier</option>
            <option>AC First Class</option>
        </select><br><br>
        <button type="button">Search Train</button>
    </form>

    <h2>Available Trains</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Train No.</th>
            <th>Train Name</th>
            <th>Departure</th>
            <th>Availability</th>
            <th>Fare</th>
        </tr>
        <tr>
            <td>12601</td>
            <td>Express Train</td>
            <td>08:00 AM</td>
            <td>Available</td>
            <td>Rs. 500</td>
        </tr>
        <tr>
            <td>12602</td>
            <td>Superfast Train</td>
            <td>10:00 AM</td>
            <td>Waiting List</td>
            <td>Rs. 700</td>
        </tr>
    </table>

    <h2>Book Ticket</h2>
    <form>
        Passenger Name: <input type="text" required><br><br>
        Age: <input type="number" min="1" required><br><br>
        Gender:
        <select>
            <option>Male</option>
            <option>Female</option>
            <option>Other</option>
        </select><br><br>
        Number of Tickets:
        <input type="number" min="1" required><br><br>
        <button type="button">Book Ticket</button>
    </form>

    <h2>Check PNR Status</h2>
    PNR Number: <input type="text">
    <button type="button">Check Status</button>

    <h2>Cancel Ticket</h2>
    PNR Number: <input type="text">
    <button type="button">Cancel Ticket</button>

    <h2>Refund Details</h2>
    <p>Refund amount depends on the applicable cancellation rules.</p>

    <h2>Admin Panel</h2>
    <p>Manage trains, schedules, fares, seat availability, and payment records.</p>
    <button type="button">Manage Trains</button>

    <footer>
        <hr>
        <p>&copy; 2026 Train Reservation System</p>
    </footer>
</body>
</html>

# 🏨 Hotel Room Booking Management System (C Project)

## 📌 Project Overview

This is a simple **Hotel Room Booking Management System** written in **C language**. It allows hotel staff to manage room bookings, view status, and perform check-outs. Designed with a fixed number of rooms, it demonstrates basic C programming concepts including structures, arrays, loops, and user input handling.

---

## 🚀 Features

- 📋 **View Room Status**  
  Displays all rooms with their booking status and guest names.

- 🛏️ **Book a Room**  
  Allows a user to book an available room and enter a guest name.

- 🧾 **Check Out from a Room**  
  Marks a booked room as available and clears guest details.

- ❌ **Exit**  
  Closes the application gracefully.

---

## ⚙️ How It Works

### Step-by-Step:

1. **Start** the program.
2. **Initialize rooms**:
   - Each room has a room number, booking status (`Available` or `Booked`), and a guest name.
   - All rooms are initialized as available with "Not Booked" status.
3. **Display Menu**:
   - 1: View room status
   - 2: Book a room
   - 3: Check out from a room
   - 4: Exit the program
4. **Process User Input** and perform the corresponding action.

---

## 🧑‍💻 Code Highlights

- Uses `struct Room` to store room data.
- Uses arrays for fixed-size room management.
- Clean console-based UI with basic input validation.
- Menu-driven program using `switch-case`.

---

## 💡 Sample Output

```
--- Hotel Management System ---
1. View all rooms
2. Book a room
3. Check out a room
4. Exit
Enter your choice:
```

---

## 🛠️ Compilation & Execution

### Compile:
```bash
gcc hotel_booking.c -o hotel_booking
```

### Run:
```bash
./hotel_booking
```

---

## 🧾 File Structure

```bash
hotel_booking.c       # Main source code file
README.md             # Project description
```

---

## 🏁 Future Improvements

- Add dynamic room allocation using pointers.
- Store booking data in files.
- Add features like billing, room types, and date of booking.

---

## 🧑‍🎓 Author

**Kusuma Sree**  
3rd Year B.Tech Student  
Skilled in C and Python  

---

## 📄 License

This project is open-source and free to use for educational purposes.

# Hotel Reservation System (Java Swing + OOP + File I/O)

A complete, GUI-based hotel reservation system built in Java Swing, designed
to be opened directly in **NetBeans** as a project.

## Features
1. Search, book, and manage hotel rooms.
2. Room categories: Standard, Deluxe, Suite (with different base prices).
3. User Sign Up / Sign In with validation (email format, password length,
   duplicate username checks, etc).
4. Make and cancel reservations, with confirmation dialogs before cancelling.
5. Simulated payment processing (card number validation + simulated gateway call).
6. Full OOP design (Room, Customer, Reservation, RoomCategory, HotelService,
   FileStorage) with clear separation between GUI, business logic, and
   data/file storage layers.
7. Persistent storage using flat text files (`data/rooms.txt`,
   `data/customers.txt`, `data/reservations.txt`) — created automatically on
   first run, no external database required.
8. GUI built with Swing: JFrame, JTabbedPane, JScrollPane (scrollbars),
   JTable, buttons, combo boxes, checkboxes, and room images.

## How to open in NetBeans
1. Open NetBeans → File → Open Project.
2. Select the `HotelReservationSystem` folder (it already contains
   `nbproject/`, so NetBeans will recognize it as a Java project).
3. Right-click the project → Clean and Build.
4. Right-click `Main.java` (in `com.hotel` package) → Run File.

## How to run from the command line (alternative)
```
cd HotelReservationSystem
javac -d build $(find src -name "*.java")
java -cp build com.hotel.Main
```

## Folder Structure
```
HotelReservationSystem/
├── src/com/hotel/
│   ├── Main.java                  (entry point)
│   ├── model/                     (Room, Customer, Reservation, RoomCategory)
│   ├── service/HotelService.java  (business logic / OOP core)
│   ├── util/FileStorage.java      (file I/O persistence layer)
│   └── gui/                       (LoginFrame, MainFrame, BookingPanel,
│                                    MyReservationsPanel, ImageUtil)
├── images/                        (room images: standard.png, deluxe.png,
│                                    suite.png, logo.png — placeholders,
│                                    replace with your own photos any time)
├── data/                          (auto-created on first run — rooms,
│                                    customers, reservations text files)
└── nbproject/                     (NetBeans project config)
```

## Notes
- The `images/` folder contains generated placeholder pictures for each room
  category and a logo. Just replace these PNG files with real photos (keep
  the same filenames) to instantly update the GUI — no code changes needed.
- Payment is **simulated only**: it checks the card number looks valid
  (12–19 digits) and "processes" it with a short delay; no real transaction
  occurs.
- Seven rooms are seeded automatically the first time you run the app
  (3 Standard, 2 Deluxe, 2 Suite). Edit `data/rooms.txt` directly, or extend
  `FileStorage.seedRooms()`, to add more.

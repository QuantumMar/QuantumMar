- 👋 Hi, I’m @QuantumMar
- 👀 I’m interested in creating apps.
- 🌱 I’m currently learning AI...
- 💞️ I’m looking to collaborate on creating Apps ..Art..
- 📫 How to reach me leave me a message..
- 😄 Pronouns: ...
- ⚡ Fun fact: I am a perpetual beginner who loves collaboration 😎.

<!---
QuantumMar/QuantumMar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


Python

class Bus: def __init__(self, seats): self.seats = seats self.passengers = {} def book_ticket(self, name, seat_number): if seat_number in self.passengers: return "Seat already booked!" elif seat_number > self.seats: return "Invalid seat number!" else: self.passengers[seat_number] = name return f"Ticket booked for {name} on seat {seat_number}." def cancel_ticket(self, seat_number): if seat_number in self.passengers: del self.passengers[seat_number] return f"Seat {seat_number} is now available." else: return "Seat not booked!" def show_bookings(self): return self.passengers if self.passengers else "No bookings yet." # Example usage: bus = Bus(40) # A bus with 40 seats # Booking tickets print(bus.book_ticket("Alice", 12)) print(bus.book_ticket("Bob", 17)) # Showing current bookings print(bus.show_bookings()) # Canceling a ticket print(bus.cancel_ticket(12)) # Trying to book an already booked seat print(bus.book_ticket("Charlie", 17)) # Final bookings print(bus.show_bookings(



Python

class Bus: def __init__(se

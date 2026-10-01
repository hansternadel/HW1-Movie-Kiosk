# HW1-Movie-Kiosk
Guided software engineering tools practice.
## Movie Theater Ticket Kiosk
A movie theater kiosk that is self-serviced. It allows a customer to purchase an available seat for any available movie. It shows the customers all the available movies, their respected show times and available seats. System provides confirmation of purchased ticket and prevents the same seat from being sold twice.

## Use Cases:
Purchase ticket: 
    Primary Actor: Customer
    Precondition: 1. TUCBW the customer choosing a movie, desired showtime, and specific seat, clicking enter to start the 
    purchasing process.
    Main Steps:
      2. System reserves the chosen seat for the customer.
      3. System asks if customer is a reward member.
      4. Customer clicks yes.
      5. System moves to customer information screen.
      6. User types email and or phone number linked to rewards and clicks enter.
      7. System moves to the payment screen, asking customer to swipe/tap.
      8. Customer swipes or taps their card on the card reader.
      9. Customer receives success status of the payment on the screen.
    Postcondition: TUCEW the customer receiving a printed receipt and ticket.

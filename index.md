<style>
  .floating-appointment-btn {
    position: fixed;
    bottom: 30px;
    right: 30px;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: #0366d6;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 12px;
    text-align: center;
    padding: 15px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    z-index: 1000;
    transition: all 0.3s ease;
  }

  .floating-appointment-btn:hover {
    background-color: #0256c7;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
    transform: scale(1.1);
  }
</style>

<a href="https://calendly.com/emilio-colombo/ricevimento" class="floating-appointment-btn">
  Book an Appointment
</a>
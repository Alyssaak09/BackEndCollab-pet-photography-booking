# Pet Photography Booking Web App

A collaborative web application that allows pet owners to book professional photographers for pet photo sessions. Built for managing bookings, services, and notifications in a user-friendly and efficient way.

---

## Team Assignment

| Member       | Responsibilities                          |
|--------------|--------------------------------------------|
| **Elliedd-26** | Owner, Pet, Notification features         |
| **Alyssaak09** | Photographer, Booking, Service features   |

---
## Project Links

- **GitHub Repository**: [pet-photography-booking](https://github.com/Elliedd-26/pet-photography-booking)


### Contributors

- [@Elliedd-26](https://github.com/Elliedd-26)
- [@Alyssaak09](https://github.com/Alyssaak09)

---

## Features

- User authentication (Admin & Client logins)
- Pet owner management
- Pet information handling
- Photographer management
- Booking system with scheduling
- Service type customization
- Notification system (alerts/reminders)
- Image uploading (pet/photo galleries)

---

## Tech Stack

- **Backend**: ASP.NET Core MVC  
- **ORM**: Entity Framework Core  
- **Database**: SQL Server  
- **Frontend**: Bootstrap

---

## Development Rules

- Work on **individual branches**
- Push code to your branch **daily**
- Use **Pull Requests** to merge into `main`
- Communicate before modifying **shared files**

---

## Project Structure

pet-photography-booking/
├── Controllers/
│   ├── OwnerController.cs          ← Elliedd-26
│   ├── PetController.cs            ← Elliedd-26
│   ├── NotificationController.cs   ← Elliedd-26
│   ├── PhotographerController.cs   ← Alyssaak09
│   ├── BookingController.cs        ← Alyssaak09
│   └── ServiceController.cs        ← Alyssaak09
├── Models/
│   ├── Owner.cs                    ← Elliedd-26
│   ├── Pet.cs                      ← Elliedd-26
│   ├── Notification.cs            ← Elliedd-26
│   ├── Photographer.cs            ← Alyssaak09
│   ├── Booking.cs                 ← Alyssaak09
│   └── Service.cs                 ← Alyssaak09
├── Views/
│   ├── Owner/                      ← Elliedd-26
│   ├── Pet/                        ← Elliedd-26
│   ├── Notification/               ← Elliedd-26
│   ├── Photographer/               ← Alyssaak09
│   ├── Booking/                    ← Alyssaak09
│   └── Service/                    ← Alyssaak09
├── Data/
│   └── ApplicationDbContext.cs
└── wwwroot/

---
## Entity Relationships
- Owner (1) → (M) Pet

- Owner (1) → (M) Booking

- Owner (1) → (M) Notification

- Pet (1) → (M) Booking

- Photographer (1) → (M) Booking

- Photographer (1) → (M) Service

- Photographer (1) → (M) Notification

- Service (1) → (M) Booking

- Booking (1) → (M) Notification

---
## Development Timeline

| Milestone              | Date            |
|------------------------|-----------------|
| MVP Completion         | July 18, 2025   |
| Creative Collaboration | August 1, 2025  |
| Final Documentation    | August 15, 2025 |




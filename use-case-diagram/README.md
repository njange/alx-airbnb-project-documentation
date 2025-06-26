# Use Case Diagram: ALX Airbnb Project


## Actors
- **Guest**
- **Host**
- **Admin**

## Use Cases
- **User Registration**
- **Login**
- **Browse Properties**
- **Book Property**
- **Make Payment**
- **List Property**
- **Manage Bookings**
- **Manage Users** (Admin)
- **View Reports** (Admin)

## Interactions

- **Guest**:
    - Register
    - Login
    - Browse Properties
    - Book Property
    - Make Payment
    - Manage Bookings

- **Host**:
    - Register
    - Login
    - List Property
    - Manage Bookings

- **Admin**:
    - Login
    - Manage Users
    - View Reports

## Diagram Example

```mermaid
actor Guest
actor Host
actor Admin

Guest --> (Register)
Guest --> (Login)
Guest --> (Browse Properties)
Guest --> (Book Property)
Guest --> (Make Payment)
Guest --> (Manage Bookings)

Host --> (Register)
Host --> (Login)
Host --> (List Property)
Host --> (Manage Bookings)

Admin --> (Login)
Admin --> (Manage Users)
Admin --> (View Reports)
```

> **Tip:** Use [Draw.io](https://draw.io) to visually create this diagram. Add actors as stick figures and use cases as ovals. Connect actors to their relevant use cases with lines.

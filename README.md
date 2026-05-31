# MediBook---Hospital-Appointment-System
best hospital management system in kigali
MediBook - Hospital Appointment System
A clean, modern UI/UX design for a mobile hospital appointment booking system, built in Figma.
Figma Design File
View the full design on Figma

Overview
MediBook is a hospital appointment booking app designed for a smooth and stress-free patient experience. The design covers the full booking journey from finding a doctor to receiving a confirmed appointment with a QR check-in code.

Screens
ScreenDescriptionHome / DashboardWelcome screen with quick actions and upcoming appointmentsFind a DoctorSearch and filter doctors by specialtyDoctor ProfileDoctor bio, experience, ratings and available slotsSelect Date & TimeCalendar picker and time slot selectionPatient DetailsForm for personal info, reason for visit and insuranceBooking ConfirmationSummary card, QR code and add-to-calendar optionMy AppointmentsUpcoming, completed and cancelled appointments list

Design Decisions
Typography — Inter / Plus Jakarta Sans. Sizes: 22px heading, 15px body, 12px caption.
Color palette

Primary: #1A73E8 (blue) — CTAs, selected states, links
Success: #0F9D58 (green) — confirmed status, available slots
Warning: amber — pending status, reminders
Neutral: #F5F5F5 background, #9E9E9E secondary text

Spacing — 4px base scale: 4 / 8 / 12 / 16 / 24 / 32 / 48px
Corner radius — Cards 16px · Buttons 12px · Chips 20px · Inputs 10px
Grid — 4-column, 16px margin, 16px gutter (frame size: 390 x 844px — iPhone 14)

Components

Doctor card (compact + expanded variants)
Calendar widget (available / unavailable / selected / today states)
Time slot chip (open / booked / selected variants)
Primary button (default / pressed / disabled)
Input field (default / focused / error)
Specialty filter chip (active / inactive)
Progress stepper (4-step)
Appointment item (confirmed / pending / completed / cancelled)
Status badge


User Flow
Home -> Find a Doctor -> Doctor Profile -> Select Date & Time -> Patient Details -> Confirmation

Tools Used

Figma — UI design and prototyping
Tabler Icons — icon set (outline style)
Iconify plugin — icon management inside Figma


Figma File Structure
Pages
├── Style Guide     -> colors, typography, spacing tokens
├── Components      -> all reusable components with variants
├── Screens         -> all 7 screens
└── Flow            -> user journey with prototype connections

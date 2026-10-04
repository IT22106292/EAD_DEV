# Part 1 — IT22166210 Sewmini G.L.C — Reservations & Prosumer Booking Flow (25%)

**Weight:** 25% of full report (~110 of ~444 pages equivalent)
**Theme:** Energy trading lifecycle + prosumer mobile booking experience

## A. Documentation Sections to Own
- [ ] 1. Executive Summary — Prosumer booking paragraph + Key capabilities (7-day / 12-hour / QR)
- [ ] 2.4 REST API Reference — Table 7 `Reservations` + Diagnostics (verify-qr, dashboard-stats)
- [ ] 3.1 MongoDB — Table 11 `EnergyBookingSlots` + Table 12 `EnergyReservation` (fields, constraints)
- [ ] 3.4 Business Rules — 7-day window, 12-hour notice, lifecycle Approved→Completed/Cancelled, Rs 45.00/kWh, slot allocation
- [ ] List of Tables/Figures entries for Tables 7, 11, 12

## B. Code Paste Scope (Section 4)
**4.1 Backend:**
- [ ] `ReservationsController.cs` (full)
- [ ] `ReservationService.cs` (Create / Update / Cancel / VerifyAndComplete + QR signing)
- [ ] `ReservationDtos.cs`, `EnergyReservation.cs`, `EnergyBookingSlots.cs`, `EnergyTransaction.cs`

**4.3 Android — Prosumer booking:**
- [ ] `CreateReservationActivity.java` + `activity_create_reservation.xml` + dialogs (`dialog_confirm_booking`, `dialog_pick_datetime`, `dialog_edit_reservation`)
- [ ] `BookingHistoryActivity.java` + `BookingDetailActivity.java` + `item_booking.xml`, `item_history.xml`
- [ ] `EnergyTransferHistoryActivity.java` + `item_energy_transfer.xml`

**4.2 Web (supporting):**
- [ ] Booking list / filter / dashboard-stats call (Axios) + related modals

## C. Other Report Parts
- [ ] 5. Screenshots — Prosumer booking, history, detail, QR display (mobile + web live queue)
- [ ] 5. Inventories — Reservation-related rows in Page Inventory + Activity table
- [ ] 6. Individual Contributions — IT22166210 detailed breakdown
- [ ] 7. Challenge 2 — 7-Day & 12-Hour synchronous enforcement
- [ ] 8. References — Reservation / QR / transaction sources (3–4 refs)

## D. Definition of Done
Report sub-section compiles, all claims verified in code, screenshots taken from running app, code pastes complete with headers.

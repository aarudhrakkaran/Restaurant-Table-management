# Restaurant-Table-management
This is a restaurant management system built using python and SQL ,web based. Features: Add tables, combine table, waitlist, color-coded waiting table status, FIFO concept implementation, Billing with customizable Tax and tips, Printable bills, Assignable waiters, Revenue calculation , Inventory Management.

A More Detailed information on this project:
This full-stack Restaurant Management System combines front-of-house table visualization, FIFO order processing, floor plan customization, and billing automation powered by a relational SQLite database structure.

Core Features
Visual Floor Plan & Live Wait Timers: Dynamic board reflecting real-time table statuses using distinct color coding—Green (Empty), Yellow (Occupied with active live timers tracking wait duration), and Red (Ordered/Eating).

FIFO Priority Engine & Waitlist: Built-in First-In, First-Out queueing system that prioritizes seated orders and walk-in guests by exact arrival time to streamline kitchen workflow.

Dynamic Table Management: On-the-fly table creation with custom seat capacities, plus the ability to combine/merge adjacent tables along with their active orders.

Categorized Menu & Order Holding: Categorized menu navigation with quick search, live quantity adjustments, and background order holding for active tables.

Custom Billing, Tax & Discount Engine: Automated subtotal calculations with dynamic tax rate adjustments (presets from 0% to 18%), percentage or flat discounts, tip selections, and table release upon settlement.

Printable Thermal Receipts: Clean printable receipt layouts featuring itemized unit costs, breakdown of subtotals, applied discounts, tax totals, gratuities, and barcode footers.

Live SQL Transaction Logger: Transparent database integration executing real-time INSERT, UPDATE, DELETE, and SELECT queries across relational schema tables (tables, menu, orders, and waitlist).

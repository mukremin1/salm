# Market Cashier Simulation Game - Specification

## Game Overview
- **Game Name**: Süper Kasalı (Super Cashier)
- **Type**: Market Simulation / Tycoon Game
- **Language**: Turkish (as requested)
- **Platform**: Web Browser (HTML5)

## Core Features

### 1. Cashier Simulation System
- Customer queue with randomized customers
- Products with prices: 
  - Ekmek (Bread) - 5 TL
  - Süt (Milk) - 15 TL
  - Yumurta (Egg) - 20 TL
  - Peynir (Cheese) - 45 TL
  - Et (Meat) - 120 TL
  - Meyve (Fruit) - 25 TL
  - Sebze (Vegetables) - 18 TL
  - Su (Water) - 3 TL
  - Çay (Tea) - 10 TL
  - Kahve (Coffee) - 20 TL
- Click to add items to cart
- Calculate total price
- Handle payment (simulated money)
- Give change back

### 2. Level System
- **Level 1-5**: Basic cashier (10 customers/day target)
- **Level 6-10**: Advanced cashier (unlock premium products)
- **Level 11+**: Can open own market
- XP gained per successful transaction
- Bonus XP for no mistakes

### 3. Quest System (Görevler)
- "İlk Gün" (First Day): Serve 5 customers
- "Hız Kasabı" (Speed Demon): Serve 10 customers in record time
- "Vip Müşteri" (VIP Customer): Handle a customer with 200+ TL order
- "Hatasız Kasar" (Flawless Cashier): 5 perfect transactions in a row

### 4. Own Market Feature (Level 11+)
- Hire employees (cashiers)
- Stock products automatically
- Earn passive income
- Upgrade market level for more income
- Unlock new product categories

## UI/UX Design

### Visual Style
- Retro pixel-art inspired design
- Warm color palette (orange, brown, cream)
- Clean, friendly interface
- Smooth animations for interactions

### Layout
- Left side: Customer and products
- Center: Cash register/calculator
- Right side: Stats and quests
- Bottom: Level progress bar

### Color Scheme
- Primary: #E67E22 (Orange)
- Secondary: #8B4513 (Brown)
- Background: #FDF6E3 (Cream)
- Success: #27AE60 (Green)
- Warning: #F39C12 (Yellow)

## Technical Implementation
- Single HTML file with embedded CSS and JS
- LocalStorage for saving progress
- Responsive design for different screens

## Acceptance Criteria
1. ✅ Can serve customers by clicking products
2. ✅ Correct calculation of totals
3. ✅ Level up system works
4. ✅ Quests unlock at appropriate levels
5. ✅ Own market feature unlocks at level 11
6. ✅ Progress saves to localStorage


# Finance budget app (logic)

# Overview

Mobile app for planning a budget for several people, friends when they went somewhere, or family budget planning.

### Main features

**Journey budget.** there will be an ability to create a room where you can add several people via a link or by searching room-name. In that room will be an overview of why this room was created and the estimated budget that will be spent. People inside that room can add how much money they spent with a quick description of the reason. At the end of the journey, the app will calculate equally how much each person should pay or be paid in return if needed.

**Family budget.** there will be a room for members of a family. Each member can see how much money have in each member including bank invoices, card sums, and hand money sums. The overall sum also will be displayed. with estimated outcomes of who will spend for in time being. there will be also a feature that selected the main budget card, the ability for family members to transfer money to a member’s card.

**Personal budget.** Personal budget room, where will be indicated how much money they have. How much money they spent or might be spent in time being. Outcome and incomes.

### Scratch

**Pages**

1. Main page

2. Room select page

3. Room page looks like a chat room

### Technical side

**Database scheme.**

users

— id

— name

— email

— password

rooms

— id

— name

— overview

— created_at

— created_by

room_budget

— id

— room_id

— isIncome

— description

— amount

— created_at

— created_by

tags

— id

— room_id

— name

Default tags.

— future outcome

— future income

— meal

— custom

— budget money

Link format

    room_id-user_id

# Accounting Design
## Prepay 
#### 1. Place Order
```
Dr. Cash
    Cr. Unearned Revenue
```
#### 2. Buy Inventory
```
Dr Invenotry
    Cr. Cash
```
#### 3. Ship
```
Dr. Shipping Expanse
    Cr. Cash
```
#### 4. Confirm Delivery
```
Dr. Unearned Revenue
    Cr. Revenue
```
## Prepay Deposit
#### 1. Place Order
```
Dr. Cash
    Cr. Customer Deposit
```
#### 2. Buy Inventory
```
Dr. Inventory
    Cr. Cash
```
#### 3. Balance Payment
```
Dr. Cash
    Cr. Unearned Revenue
```
#### 4. Ship
```
Dr. Shipping Expanse
    Cr. Cash
```
#### 5. Confirm Delivery
```
Dr. Unearned Revenue
Dr. Customer Deposit
    Cr. Revenue
```
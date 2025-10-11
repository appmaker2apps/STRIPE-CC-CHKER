# Stripe CC Checker

## Description
This script checks credit card validity using the Stripe API. It reads card details from a file (`cc.txt`), processes them, and saves the results in `results.txt`.

## Features
✅ Reads credit cards from `cc.txt`  
✅ Uses Stripe API to verify cards  
✅ Saves results to `results.txt`  
✅ Handles errors & invalid formats  

## Requirements
-Windows
-Internet Connection

## Usage
1. Add credit card details to `cc.txt` in this format:
   ```
   4242424242424242 | 12 | 2025 | 123
   4000056655665556 | 11 | 2024 | 456
   ```
   
2. Run the EXE
   
4. Results will be saved in `results.txt`.

## Output Format
Each line in `results.txt` will show the card status:
```
4242424242424242 | 12 | 2025 | 123 - Approved ✅
4000056655665556 | 11 | 2024 | 456 - Declined ❌ (Card declined)
```

## Warning ⚠️
- **i am NOT hold accountable for what you do with this tool**

## License
MIT License

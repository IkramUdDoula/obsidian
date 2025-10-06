## Notes

- 
## To Do Lists

- [ ] LLM selection based on prompt
- [ ] default - aperatus, llama, maverick
- [ ] text to speech in mobile - priority
- [ ] promo code


- **Feature:** Promo code (voucher code) field at checkout/cart
    
- **Functionality:**   
    - Customers can enter a code (in the EagleGPT app checkout page), apply it, and see the discount automatically deducted and displayed.
    - The field must be user-friendly and clearly visible. 
    - Demo - ![[Pasted image 20251006154255.png]]
    - Show clear error messages for invalid or expired codes.
    - Discount must integrate correctly into the total amount.
    - Discounted amount must be shown in the summary. 
- **Admin Requirements:**
    - Administrators must be able to easily add, change, or delete promotion details (name, discount, validity, redemption rules, and duration—e.g., 1 month, 12 months, or lifetime).
    - Admins will use the Cloud Application for the configuration.
    - Discount configuration
- Discount Configuration:
	- **Discount Type**     
	    - Dropdown to select type (percentage, fixed amount, special campaign, etc.)      
	- **Discount Value**    
	    - Numeric input for percentage or fixed value
        
- **Discount Code**    
    - Text input for code (if user applies manually)        
- **Eligibility Criteria**    
    - Dropdown or checklist (user segment: new user, returning, enterprise, etc.)        
    - Specific product/service selection (multi-select)        
- **Active Dates*    
    - Start date & end date pickers for validity        
- **Usage Limits**    
    - Maximum uses per user        
    - Global maximum uses        
    - Limit per order/session        
- **Stacking & Restrictions**
    - Can be combined with other offers? (checkbox)        
- **Status**    
    - Active/Inactive toggle        
- **Description**    
    - Text area for explanation, notes, or conditions        

**Optional Advanced Fields:**

- **Minimum Purchase Requirement**
    
    - Numeric input for order value threshold
        
- **Payment Method Restrictions**
    
    - Multi-select for allowed payment methods (e.g., Stripe, PayPal)
        
- **Geographical Limitations**
    
    - Multi-select for regions/countries
        
- **Automated Rules**
    
    - Add rule builder for auto-application based on user behavior or triggers
- **Timeline:**  
    Go-live is expected by October 20, 2025.



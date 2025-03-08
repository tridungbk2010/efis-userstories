# US6.3: Promo Code Application

## User Story

**As a** student  
**I want to** apply a promotional code to my purchase  
**So that** I can receive applicable discounts

## Acceptance Criteria

1. System provides a clearly visible promo code field on the checkout page
2. User can enter and apply a promo code before completing payment
3. System validates the promo code in real-time
4. System displays clear feedback on promo code validity:
   - Valid: Shows discount amount and updates total price
   - Invalid: Shows error message with reason (expired, invalid, etc.)
5. User can remove an applied promo code to revert to original pricing
6. System prevents applying multiple promo codes unless specifically allowed
7. System logs all promo code usage for analytics

## Details

**Story Points:** 3  
**Priority:** Medium  
**Epic:** [Epic 6: Payment](./README.md)

## Implementation Notes

- Implement secure server-side validation for all promo codes
- Design clear visual feedback for code application status
- Create a flexible promo code system supporting:
  - Percentage discounts
  - Fixed amount discounts
  - Free add-ons or upgrades
  - Time-limited offers
- Ensure promo code validation is performed before payment processing
- Add analytics tracking for promo code usage and conversion rates
- Implement rate limiting to prevent brute force attempts
- Create admin interface for managing promo codes (creation, expiration, limits)

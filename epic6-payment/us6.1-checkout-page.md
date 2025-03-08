# US6.1: Checkout Page

## User Story

**As a** student  
**I want to** see a clear checkout page with order details  
**So that** I can review my purchase before payment

## Acceptance Criteria

1. System displays a comprehensive checkout page after package selection
2. Checkout page includes:
   - Selected course package name and description
   - Itemized price breakdown
   - Total amount to be paid
   - Order summary
   - Available payment methods
   - Promo code field
3. Page is responsive and works on all devices
4. User can return to package selection if needed
5. All pricing information is clearly displayed in both VND and USD

## Details

**Story Points:** 5  
**Priority:** High  
**Epic:** [Epic 6: Payment](./README.md)

## Implementation Notes

- Design a clean, distraction-free checkout interface
- Implement responsive design for all device sizes
- Ensure all text is clearly readable with appropriate contrast
- Include a progress indicator showing checkout stage
- Add a "Return to Selection" option that preserves selections
- Implement currency conversion with current exchange rates
- Ensure all pricing calculations are performed server-side
- Add analytics tracking for checkout page views and abandonment

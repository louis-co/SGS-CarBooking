# SGS-CarBooking

## V 1.0.0.0_Prod 
#### LOH + SOY + PHWE

- Set up The car booking env + all the flows and Event registration Updates needed for CarB
- Transferred work form Dev to Prod
  - Systemuser
  - eventregistration
  - contact (foreign view)
  - Custom App
  - Admin and User Roles
- Flows
    - Characteristics Inheritor (from Car to Driver)
    - Name setter (if not shuttle -> Name : FromLocation - ToLocation
    - Google Maps Duration Api Getter Flow (also gets Addresses)

## V 1.0.0.1_Prod
#### LOH
- Fixed Flow the duration multiplier (there was a type issue) Flow in question: Google Maps Duration Api Getter Flow (also gets Addresses)
- Minor Name Changes of flow: Google Maps Duration Api Getter Flow (also gets Addresses)

## V 1.0.0.2_Prod (skipped)
## V 1.0.0.3_Prod (skipped)

## V 1.0.0.4_Prod
#### LOH
- Redid Changes in the duration inserter (the multiplier got deleted somehow)
- Redid Changes in the forms getter so its ready for prod (unbekannter beifahrer is now also in prod) 
- Removed Forms flow from solution after import to be able to fix stuff in prod directly
- Changed the fetch xml of contacts to ones that are registered in the symposium that has isCurrentSymposium eq true
- 

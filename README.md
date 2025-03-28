# Signatures
Contains the needed images to provide the HTML code the link to display them.
Contains the base code with variables that should be filled with personal info depending on the user of the signature:
  - Name
  - Function
  - Mobile number (Tel)
  - Mobile number (Display)
  - Email (Mailto)
  - Email (Display)
  - Profile image path

## Code of Conduct
- Every kind of image has it's own directory
  - Banners
  - Profiles
  - Shared (for all signatures)
- Use the same naming conventions to make adjustments easier

## Usage
This methode is used because Outlook processes signatures in HTML wrong by lining them out to the left, braking the indentations.
The webversion does proces it to some degree, but other then this methode it will still brake when using the app.

- Adjust the code as needed for the profile.
- Save the code as a html file and send it to the user
- User opens the file and sees the signature in the browser
- User copy's the signature and pastes it into the webversion of outlook as a signature.
- Save the signature
- The user can now use the signature to send e-mails

>[!Note]
>The signature will not be immediately available in de outlook app.
>Close the application and start it back up again if the synchronisation takes longer then 30min.

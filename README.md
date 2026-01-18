# Test Case: AWS Gmail Login

**Test Case ID:** TC-Login-01  
**Test Title:** AWS - Valid login through Gmail account  

## Preconditions
- User has a working Gmail account synced to their device  
- Browser: Chrome 143.0.7499.193 (Official Build) (arm64)  
- OS: macOS Sonoma 14.6.1  
- Device: MacBook Air  

## Test Steps
1. Navigate to AWS login page: `https://aws.amazon.com/`  
2. Click the **user icon** in the top-right corner  
3. Select **Login** from the dropdown menu  
4. Click **Continue with Google**  
5. Select your Gmail account and click **Continue to sign in**  

## Expected Result
- User is logged in successfully  
- User is redirected to the AWS dashboard  
- AWS console fully loads with user account menu accessible  

## Actual Result
- Login failed with error:  
  `"It's not you, it's us. We couldn't complete your request right now. Please try again later."`  
- Request ID: 72654aef-5eca-47f0-803e-1763a5a9bd4a  
- Time: Sun, 18 Jan 2026 20:32:07 GMT  

## Test Outcome
FAIL  

## Notes
- Issue may be due to temporary AWS authentication service error  
- Screenshot attached for reference

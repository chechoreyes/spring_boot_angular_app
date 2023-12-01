# Application requeriments

## Aplication user

1. User new account (unique email address)
    - Account verification (Verify email address)
    - User profile image
    - User details (name, email, position, bio, phone, address, etc)
    - Being able to update user detail information
2. User reset password (without being logged in)
    - Password reset link sould expire in 24 hours
3. User login (using email and password)
    - Token based authentication (JWT Token)
    - refresh Token seamslessly
4. Brute force attack mitigation (account lock mechanism)
    - Lock account on 6 failed login attemps]
5. Role and Permission based application access (ACL)
    - Protect application resources using roles and permisions
6. Two-factor authentication (using user phone number)
    - Send verification code to user's phone
7. Keep trakc to user activities (login, account change, etc)
    - Ability to report suspicious activities]
    - Tracking information
      - IP Address
      - Device
      - Browser
      - Date
      - Type

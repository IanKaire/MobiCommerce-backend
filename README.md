![server on render](https://github.com/IanKaire/MobiCommerce-backend/assets/114652346/99852ff3-ce33-4ad7-8ab5-e05ca09ca281)
![server on browser](https://github.com/IanKaire/MobiCommerce-backend/assets/114652346/7b953e94-d73d-4f8a-a779-d2c050432a7b)
![server on postman](https://github.com/IanKaire/MobiCommerce-backend/assets/114652346/65a3276b-1c5e-49a7-806a-779122e38c3a)

# MobiCommerce-backend
The backend logic for MobiCommerce an ecommerce mobile platform based on the M.E.R.N (MongoDB, Express, React Native and NodeJS) stack.
Here is the URL: https://mobicommerce-server.onrender.com/. It should display "Working" when you visit it.
# Setup
i. A.P.Is

        User:
                      ● Login
                      ● Signup
                      ● getMyProfile
                      ● Logout
                      ● updateProfile
                      ● changePassword
                      ● updatePic
                      ● forgetPassword
                      ● resetPassword
        Product:
                      ● getAllProducts
                      ● getAdminProducts
                      ● getProductDetails
                      ● updateProduct
                      ● deleteProduct
                      ● createProduct
                      ● addProductImage
                      ● deleteProductImage
                      ● addCategory
                      ● getAllCategories
                      ● deleteCategory
        Order:
                      ● createOrder
                      ● processPayment
                      ● getMyOrders
                      ● getAdminOrders
                      ● getOrderDetails
                      ● processOrder

ii. Schemas

          User:
                      ● Name
                      ● Email
                      ● Password
                      ● Address
                      ● City
                      ● Country
                      ● PinCode
                      ● Role
                      ● Avatar
                      ● Otp
                      ● Otp_expire
          Product:
                      ● Name
                      ● Description
                      ● Price
                      ● Stock
                      ● Images
                      ● Category
                      ● CreatedAt
          Category:
                      ● Category
          Order:
                      ● ShippingInfo
                      ● OrderItems
                      ● User
                      ● PaymentMethod
                      ● PaidAt
                      ● PaymentInfo
                      ● ItemsPrice
                      ● TaxPrice
                      ● ShippingCharges
                      ● TotalAmount
                      ● OrderStatus
                      ● DeliveredAt
                      ● CreatedAt
                      
iii. Config Variables

                      1. PORT = What should be the port number
                      2. NODE_ENV = Specify the environment mode
                      3. MONGO_URI = MongoDB Uri string to connect with the database
                      4. JWT_SECRET = Any random string will work as the secret for creating a JWT token
                      5. CLOUDINARY_NAME = Cloud name provided by Cloudinary
                      6. CLOUDINARY_API_KEY = Cloudinary API Key provided by Cloudinary
                      7. CLOUDINARY_API_SECRET = Cloudinary API Secret provided by Cloudinary
                      8. SMTP_HOST = Mail Provider Host
                      9. SMTP_PORT = Mail Provider Port
                      10. SMTP_USER = Mail Provider Username
                      11. SMTP_PASS = Mail Provider Password
                      12. STRIPE_API_KEY = Stripe Publishable API Key provided by stripe
                      13. STRIPE_API_SECRET = Stripe API Secret provided by stripe

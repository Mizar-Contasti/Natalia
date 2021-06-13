Natalia es una Asistente de Restaurante, esta puede ofrecer funcionalidades dependiendo del rol que cumple el cliente.

## Estructuran de Roles

### Visitante
> - Menu
> - Contacto
> - Página Web
> - Faq
> - Registro de Cuenta

### Comensal
> - Inicio de Sesión
> - Recuperación de Sesión
> - Recuperación de Contraseña
> - Pagos
> - Reserva de Mesas
> - Envío de Promociones
> - Historial de Comensal

**==========================================**

## Intenciones

### Basics
> - basics_welcome
> - basics_start
> - basics_thanks
> - basics_bye

### Identity
> - identity_whoYouAre
> - identity_areYouARobot
> - identity_whatYouCanDo
> - identity_whoCreatedYou


### Info
> - info_order
> - info_delivery
> - info_workHours
> - info_location
> - info_privacyPolicy
> - info_cookiePolicy
> - info_covid
> - info_webPage
> - info_contactUs

### Menu
> - menu_categories
> - menu_products

### Visitor
> - visitor_signUp
> - visitor_validate

### Customer
> - customer_logIn
> - customer_profile
> - customer_updateProfile
> - customer_recoverSession
> - customer_recoverPassword
> - customer_updatePassword
> - customer_order


**==========================================**

## Base de Datos
### Credenciales
> - codexcel_natalia
> - codexcel_mizar
> - mizar

### Modelos
> - Sessions
   - session_id
   - session_createdAt

> - Visitors
   - visitor_id
   - visitor_name

> - Customers
    - customer_id
    - customer_email
    - customer_password
    - customer_firstName
    - customer_lastName
    - customer_createdAt
    - customer_lastOrder
    - customer_lastPayment

> - Products
    - product_id
    - product_category
    - product_name
    - product_price
    - product_description
    - product_image
    
> - Categories
    - category_id
    - category_name
    - category_description
    - category_image

> - Tables
    - table_id
    - table_number
    - table_places
    - table_description
    - table_img
    - table_price

> - StatusPayment
   - status_id
   - status_name
   - status_description
   - status_img

> - TimeBlocks
   - block_id
   - block_average
   - block_availability
   - block_value

> - Bookings
   - booking_id
   - booking_customerId
   - booking_paymentId
   - booking_tableId
   - booking_blockId


> - Payments
    - payment_id
    - payment_createdAt
    - payment_statusId
    - payment_totalId
    - payment_totalArticles

> - Preorder (FUTURE IMPLEMENTATION)
   - preorder_id
   - preorder_name
   - preorder_description
   - preorder_price
   - preorder_image


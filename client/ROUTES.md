# Application Routes

This document provides a comprehensive overview of all routes available in our student learning platform application, explaining their purpose and functionality.

## Main Routes

### Home Page

- **Path:** `/`
- **Description:** The landing page showcasing trending courses, newest courses,and a contact form. It serves as the entry point to the application, highlighting key offerings and promotional content.
- **Features:**
  - Hero section with call-to-action buttons
  - Trending courses section
  - Newest courses section
  - Contact form

## Course Routes

### Courses Page

- **Path:** `/courses`
- **Description:** A comprehensive catalog of all available courses with advanced filtering capabilities.
- **Features:**
  - Filtering by category, level, language, price range, and rating
  - Search functionality (filter by title, instructor, or tags)
  - Sort options (Most Popular, Highest Rated, Newest, Price)
  - Responsive design with sidebar filters for desktop and sheet for mobile
  - Grid layout for course display with CourseCard components

### Course Detail Page

- **Path:** `/courses/[id]`
- **Description:** Detailed view of a specific course, providing comprehensive information about the course content, instructor, reviews, and related courses.
- **Features:**
  - Course overview (title, subtitle, description, price)
  - "What you'll learn" section
  - Course curriculum with accordion sections
  - Instructor information
  - Student reviews
  - Related/similar courses
  - Add to cart and wishlist functionality

## Instructor Routes

### Instructors Page

- **Path:** `/instructors`
- **Description:** A comprehensive listing of all instructors on the platform.
- **Features:**
  - Filtering by specialization, and rating
  - Search functionality to find instructors by name, role, or specialization
  - Sorting options (popularity, rating, courses, name(A-z), name(Z-A) )
  - Responsive design with sidebar filters for desktop and sheet for mobile

### Instructor Detail Page

- **Path:** `/instructors/[id]`
- **Description:** Detailed profile page for a specific instructor.
- **Features:**
  - Instructor profile header with social media links
  - Tabbed interface for courses, reviews, and about sections
  - Course listing showing the instructor's courses

## Authentication Routes

### Login Page

- **Path:** `/log-in`
- **Description:** Allows existing users to authenticate and access their account.
- **Features:**
  - Email/password login form
  - Forgot password link

### Sign Up Page

- **Path:** `/sign-up`
- **Description:** Allows new users to create an account on the platform.
- **Features:**
  - Registration form with email, password, and name fields

### Forgot Password Page

- **Path:** `/forgot-password`
- **Description:** Allows users to initiate the password recovery process.
- **Features:**
  - Email input form
  - Submit button to send recovery email

### Reset Password Page

- **Path:** `/reset-password`
- **Description:** Allows users to set a new password after receiving a reset link.
- **Features:**
  - New password and confirm password fields
  - Submit button to update password

## User Account Routes

### User Profile Page

- **Path:** `/profile`
- **Description:** User profile management page.
- **Features:**
  - Personal information management

### My Courses Page

- **Path:** `/my-courses`
- **Description:** Displays all courses that the user has purchased.
- **Features:**
  - List of enrolled courses
  - Progress tracking
  - Continue learning buttons
  - View course details

### Wishlist Page

- **Path:** `/wishlist`
- **Description:** Displays all courses that the user has added to their wishlist.
- **Features:**
  - List of wishlist courses
  - Add to cart functionality
  - Remove from wishlist functionality
  - open course details page

## Shopping Routes

### Cart Page

- **Path:** `/cart`
- **Description:** Shopping cart where users can review items before purchase.
- **Features:**
  - List of courses in cart
  - Price summary
  - Remove item functionality
  - Proceed to checkout button
  - Coupon/discount code input

### Checkout Page

- **Path:** `/checkout`
- **Description:** Checkout process for purchasing courses.
- **Features:**
  - Payment information form
  - Order summary
  - Complete purchase button

## Category Routes

### Categories Page

- **Path:** `/categories`
- **Description:** Displays all course categories available on the platform.
- **Features:**
  - Grid or list of categories
  - Link to filtered course listing by category

## API Routes

The application also includes various API routes (not directly accessible by users) that handle data fetching, form submissions, authentication, and other backend functionality. These routes are used internally by the frontend components to communicate with the server.

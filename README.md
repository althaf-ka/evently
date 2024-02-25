
# Evently

Next.js 14-based events platform for global event management. Effortless ticket purchase via Stripe, empowering users to attend or organize diverse events.

# Tech Stack

- Node.js
- Next.js
- TypeScript
- TailwindCSS
- Stripe
- Zod
- React Hook Form
- Shadcn
- Uploadthing
- Clerk Auth

# Features

#### Authentication (CRUD) with Clerk
- User management through Clerk, ensuring secure and efficient authentication.

#### Events (CRUD)
- Users can Create new events, providing essential details such as title, date, location, and additional information.

- Easy access to detailed event information, allowing users to view event specifics such as descriptions, schedules, and related details.

- Empowering users to dynamically modify event details, ensuring accurate and up-to-date information.

- Straightforward process for removing events, giving administrators effective control over platform curation.

#### Related Events
- Smartly connects related events, displaying them on the event details page for enhanced user engagement.

#### Organized Events
- Efficient organization of events, ensuring a structured and user-friendly display, such as showing user-created events on the user profile.

#### Search & Filter
- Robust search and filter system, enabling users to easily find events that match their preferences.

#### New Category
- Dynamic categorization allows seamless addition of new event categories, keeping the platform adaptable.

#### Checkout and Pay with Stripe
- Smooth and secure payment transactions using Stripe, enhancing user experience during checkout.

#### Event Orders
- Comprehensive order management system, providing a clear overview of all event-related transactions.

#### Search Orders
- Quick and efficient search functionality for orders, facilitating easy tracking and management.

#### Code Architecture and Reusability
- Structured and reusable code for easy maintenance and updates.


## Installation

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)



**Cloning the Repository**

```bash
git clone https://github.com/althaf-ka/evently
cd evently
```


Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual credentials 

**Running the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.



    

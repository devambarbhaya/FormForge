# FORMFORGE

FORMFORGE is a modern, responsive web application designed for easy creation and management of online forms. Leveraging the latest technologies, FORMFORGE offers a powerful yet intuitive drag-and-drop form designer, allowing users to build custom forms tailored to their specific needs. From simple surveys to complex data collection tasks, FORMFORGE is equipped to handle it all.

## Key Technologies

- **Next.js 13 with AppRouter**: Utilizing the latest in SSR and SSG for fast, dynamic web experiences.
- **Dnd-kit library**: For a smooth, intuitive drag-and-drop interface.
- **ServerActions**: Enhancing server-client interactions.
- **TypeScript**: Ensuring type safety and enhancing developer experience.
- **TailwindCSS / Shadcn UI**: For sleek, responsive design with minimal effort.
- **Vercel PostgreSQL**: Reliable, scalable database hosting.
- **Prisma**: As our ORM, simplifying database management with powerful, type-safe queries.

## Features

### Design & Usability
- **Responsive Design**: Ensures your form looks great on any device, from mobile phones to desktops.
- **Drag and Drop Designer**: Create forms easily with a user-friendly drag and drop interface. No coding knowledge required.

### Form Elements
- **Layout Fields**: Title, SubTitle, Spacer, Separator, Paragraph for rich form layouts.
- **Form Fields**: Includes Text, Number, Select, Date, Checkbox, Textarea. Ready for any data collection need.
- **Customizable Fields**: Easily add and customize new fields to meet the specific requirements of your form.

### Functionality
- **Form Preview Dialog**: Preview your form in a dialog to see how it looks before publishing.
- **Shareable Form URL**: Once a form is created, share its unique URL with anyone to start collecting responses.
- **Form Submission/Validation**: Built-in validation ensures that the data collected meets your specified criteria.
- **Form Stats**: Keep track of form visits and submissions with integrated statistics.

## Getting Started

To start using FORMFORGE, clone the repository and install dependencies:

```bash
git clone <repository-url>
cd formforge
npm install

DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE?schema=public"
npx prisma migrate dev
npm run dev
```


This template outlines a README.md for FORMFORGE, covering key technologies, features, getting started instructions, contribution guidelines, and acknowledgements. Adjust the repository URL and any specific installation or configuration instructions based on your project's setup.

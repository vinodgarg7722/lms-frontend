# LMS Frontend

### Setup instruction 

1. Clone the project 
...
git clone https://github.com/vinodgarg7722/lms-frontend.git
...

2. Move into the directory
...
cd lms-frontend
...

3.install dependencies
...
npm i
...

4. run the server
...
npm run dev
...


### Setup instructions for tailwind

[Tailwind official instruction doc](https://v3.tailwindcss.com/docs/installation)

1. Install tailwindcss

...
npm install -D tailwindcss
...

2. Create tailwind config file

...
npx tailwindcss init
...


3. Add file extension to tailwind config file in the content property
...
"./src/**/*.{html,js,jsx,ts,tsx}"
...

4. Add the tailwind directives at the top of the `index.css file

...
@tailwind base;
@tailwind components;
@tailwind utilities;
...

### Adding plugins and dependencies

...
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot toast @tailwindcss/line-clamp
...

### Project Dependencies & Their Functions

- **@reduxjs/toolkit** – Simplifies Redux state management by providing preconfigured tools for creating slices, reducers, and async logic (RTK Query, createAsyncThunk).
- **react-redux** – Official React bindings for Redux to connect React components with the Redux store using hooks like `useSelector` and `useDispatch`.
- **react-router-dom** – Enables navigation and routing in React apps using components like `<BrowserRouter>`, `<Route>`, and `<Link>`.
- **react-icons** – Provides a large collection of commonly used icons from libraries like FontAwesome, Feather, Material, etc., as reusable React components.
- **react-chartjs-2** – React wrapper for Chart.js to render responsive charts (bar, line, pie, etc.) in a declarative way.
- **chart.js** – The core charting library used by `react-chartjs-2` to generate beautiful and customizable charts.
- **daisyui** – A Tailwind CSS plugin that provides pre-designed UI components like buttons, modals, cards, forms with beautiful styling.
- **axios** – Promise-based HTTP client for making API requests to backend or third-party services from React.
- **react-hot-toast** – Lightweight, customizable toast notification library for showing success, error, or info messages in React apps.
- **@tailwindcss/line-clamp** – TailwindCSS plugin to truncate multi-line text with CSS line-clamp utility classes like `line-clamp-2`, `line-clamp-3`, etc.

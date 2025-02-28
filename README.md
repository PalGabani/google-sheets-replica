# Google Sheets Replica

This project is a simplified replica of Google Sheets, built using React. It aims to provide a basic interactive spreadsheet experience within a web browser.

## Features

* **Grid-based Interface:** Displays a grid of cells similar to Google Sheets.
* **Cell Editing:** Allows users to edit the content of individual cells.
* **Basic Styling:** Provides a clean and functional user interface.

## Technologies Used

* React
* (Optional: any styling library you used like styled-components, material-ui etc. add if you used)

## Getting Started

These instructions will guide you through setting up and running the project on your local machine.

### Prerequisites

* **Node.js and npm (or yarn):** Make sure you have Node.js and npm (or yarn) installed. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/PalGabani/google-sheets-replica.git
    cd google-sheets-replica
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # or if you use yarn
    # yarn install
    ```

    This command will install all the necessary packages listed in the `package.json` file, including React and other dependencies.

### Running the Application

1.  **Start the development server:**

    ```bash
    npm start
    # or if you use yarn
    # yarn start
    ```

2.  **Open in your browser:**

    The application will automatically open in your default browser at `http://localhost:3000`. If it doesn't, you can manually open it.

### Build (Optional)

If you want to create a production build of the application:

```bash
npm run build
# or if you use yarn
# yarn build

### How it Works

This React application simulates the basic functionality of Google Sheets. Here's a breakdown of how it works:

1.  **Initial Grid Display:** Upon opening the application, you'll see a grid of cells, representing the spreadsheet.

2.  **Cell Editing:**
    * Click on any cell to activate editing mode.
    * Type your desired content into the cell.
    * Press Enter or click outside the cell to save the changes.

3.  **Adding New Sheets:**
    * Look for the "Add Sheet" icon (usually a "+" symbol) located at the bottom left of the application.
    * Clicking this icon will create a new sheet, typically named "Sheet1," "Sheet2," and so on.

4.  **Sheet Navigation:**
    * After adding a sheet, the sheet name will appear as a tab or button at the bottom of the application.
    * Click on a sheet's name to switch to that sheet and perform tasks within it.
    * Each sheet will have its own independent grid.

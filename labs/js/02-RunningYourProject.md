# Lab 2: Running Your Project

## Objectives

- [ ] Run the project
- [ ] Make a change and see the app update
- [ ] Stop the project

## Steps

### Run the project

1. **Run** _one_ of the following commands:
   #### npm
   ```shell
   npm start
   ```
   #### Yarn
   ```shell
   yarn start
   ```
2. After the application builds, it will **automatically** **open** your `Chrome` **browser** to [http://localhost:3000](http://localhost:3000).

3. **Verify** the **React logo** is displayed in the browser.
   <kbd>![React Logo Screenshot](https://user-images.githubusercontent.com/1474579/65819379-bd3c8380-e1e9-11e9-9a56-b8beaa4ddfbd.png)</kbd>

### Make a change and see the app update

1.  **Add** some additional text (exclamation points) in the `render` method of the `App` component as shown below.

    #### `src\App.jsx`

    ```diff
    function App() {
    return (
        <div className="App">
        <header className="App-header">
            <img src={logo} className="App-logo" alt="logo" />
            <p>
            Edit <code>src/App.js</code> and save to reload.
            </p>
            <a
            className="App-link"
            href="https://reactjs.org"
            target="_blank"
            rel="noopener noreferrer"
            >
    -          Learn React
    +          Learn React!!!
            </a>
        </header>
        </div>
    );
    }
    ```

2.  **Verify** the additional text is displayed in your browser.

    > The page will automatically reload if you make changes to the code.

    ```
    Edit src/App.js and save to reload.
    Learn React!!!
    ```

### Stop the Project

1. **Focus** your **cursor** in the `command prompt` (Windows) or `terminal` (Mac).
2. **Type** `Ctrl + C`.
   > On `Windows` you will be prompted with `Are you sure you want to... (Y/N)`...type `y`.
3. Use what you learned earlier in the lab to **restart** the application.

---

### &#10004; You have completed Lab 2

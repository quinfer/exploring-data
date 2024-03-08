To create a Quarto Shiny app:

1. Create a new file with a `.qmd` extension (e.g., `app.qmd`).

2. Copy and paste the code above into the `.qmd` file.

3. Replace `"your_inst_token_here"` with your actual InstToken in the code.

4. Save the `.qmd` file.

5. Open the terminal or command prompt and navigate to the directory where the `.qmd` file is located.

6. Run the following command to install the required packages:

   ```
   quarto install shiny DT reticulate
   ```

7. Ensure that you have the `JCR_ABS.csv` file in the same directory as the `.qmd` file.

8. Run the app locally using the following command:

   ```
   quarto preview app.qmd
   ```

   This will start the Shiny app and open it in your default web browser.

9. To deploy the app to a server or publish it, you can use the `quarto publish` command or follow the deployment instructions specific to your server or hosting platform.

The app will have the same functionality as described earlier:
- A sidebar with dropdown menus to select the field and AJR rating.
- A "Search" button to trigger the search based on the selected field and rating.
- A datatable displaying the search results.
- A "Download CSV" button to download the search results as a CSV file.

Remember to keep your InstToken confidential and avoid sharing it publicly.

Let me know if you have any further questions!

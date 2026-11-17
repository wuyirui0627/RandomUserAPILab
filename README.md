# RandomUserAPILab — Week 11

UiPath Studio Desktop (Windows) lab project.

## Workflow
1. HTTP GET `https://randomuser.me/api/`
2. Deserialize response JSON
3. Extract `results[0].name.title`, `.first`, and `.last`
4. Display the extracted name in a Message Box

## Run
Open `project.json` in UiPath Studio Desktop, restore dependencies, and debug `Main.xaml`.

## Submission
Publish the project locally through UiPath Studio to generate the required `.nupkg` file. Submit a ZIP of the actual local project and a Word document containing a screenshot of this GitHub repository and its URL.

Note: The GitHub project was populated from the starter files available in ChatGPT. If your tested local project contains newer changes, commit and push those files from UiPath Studio before submission.

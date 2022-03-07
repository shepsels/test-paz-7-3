# Assignment
Create an editor simulating wordtune functionality.
1. There should be a wordtune button that's suggesting to "rewrite" your selected text.
This button should be placed next to the selected text.

2. Another option to trigger a "rewrite" is to click a button on the header above the editable div.
The UI should be styled a bit using css.

3. The rewrite results should be fetcheed from the mock server, and displayed in a scrollabe list.

4. a click outside the rewrite box should close it

If time permits:
1. only selected text on the editor div should trigger selection icon
2. a click on one of the suggestions should replace the selected text


# Guidlines
Proper use of components, state management and css.

# API
you can use editorUtils to:
1. register to selection change event - registerToSelectionChange
2. get mock server results - getRewriteResults

## Start the project

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

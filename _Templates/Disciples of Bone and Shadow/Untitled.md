<%*
// change to the full path of your JSON file
const jsonPath = "test.json";
const chosenJSON = await tp.app.vault.getAbstractFileByPath(jsonPath);
const jsonString = await tp.app.vault.cachedRead(chosenJSON);
const parsedJSON = JSON.parse(jsonString);
// do stuff with the results
-%>
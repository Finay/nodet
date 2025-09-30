# [Nodet](https://finay.github.io/nodet/)
A simple semi-keyboard centric node based notes app.

UI is split into 3 views: graph, editor, and navigator:
- Graphview -> Visualizes notes as nodes and connections as links
- Editorview -> Shows note content and allows editing
- Navigator -> For filtering nodes and editing links

## Usage
### Access the site [here](https://finay.github.io/nodet/)
Drag in a saved JSON file to import data.

### In graphview:
- WASD -> changes selected and next nodes
- Q -> Saves data to JSON
- I -> Insert a new node from selected node
- L -> Create a new link from selected node
- Spacebar -> Switch to editorview
- Move nodes or camera
- Select node

### In editorview:
- Escape -> Switch to graphview
- Edit title
- Edit content
- Cycle node color
- Add links
- Delete links
- Toggle link physics
- Delete node

### In navigatorview:
- Escape -> Switch to graphview
- Add/delete links
- Filter by title and content text
- Toggle filter for graphview
- Select node
- Cycle node color

[查看中文文档](https://github.com/aipio/Sidera-Force-Directed-Graph/blob/main/README-zh.md)

# Sidera —— Latin for "Stars"  
An **HTML5-based** editable force-directed graph.  

![](https://lskypro.youzhi.icu/i/2025/09/24/68d3d2e757ba4.png)

# Use Cases  
- Live teaching and demonstrations  
- Sharing inspiration and ideas  
- Embedding into webpages  
- Mapping character relationships  
- Structuring knowledge  

# Highlights  
- High degree of freedom  
- Extremely lightweight  
- Easy to use  
- Low learning curve  
- Full-featured  

# User Guide  

## Getting Started  
- On the first visit, **50 nodes** are randomly generated.  
- Use the **right mouse button** to drag a deletion box to batch delete nodes.  
  - On mobile: **long-press on blank space** and drag to draw a deletion box.  
- This creates a clean, empty canvas.  

## Feature Overview  
- When entering the graph, you will see the **bottom bar, search box, and sidebar**.  
  - By default, the bottom bar is in **Default Mode**.  
  - Additional modes include **Connect Mode** and **Canvas Mode**, each focusing on different objects.  

- **Default Mode**: Basic editing of nodes and relationships; supports batch deletion of nodes.  
- **Connect Mode**: Provides anchor points and highlighted connection lines, helping you stay focused; ideal for editing complex relationships.  
- **Canvas Mode**: Allows you to draw rectangular regions to clearly divide areas of the graph, improving readability and hierarchical organization.  
- **Search Box**: Search by keyword—any node whose title contains the keyword will be highlighted.  
- **Sidebar**: Adjust basic parameters, toggle optional features, manage the tag list, and import/export data.  

## Gestures & Controls  

- **Mouse Actions**:  
  - Scroll wheel: Zoom in/out of the canvas.  
  - Drag the canvas: Click and hold blank space.  
  - Drag nodes: Click and hold a node.  
  - Fix a node: **Shift + Click**.  

- **Default Mode**:  
  - Double-click blank space: Create a node.  
  - Double-click a node: Edit the node.  
  - Double-click an edge: Edit a bidirectional relationship.  
  - Right-click and drag: Batch delete nodes.  

- **Connect Mode**:  
  - Click two nodes: Create a connection between them.  
  - Right-click and drag: Draw a deletion line; any edge it crosses will be deleted.  
  - Double-click a node: Enter anchor mode, fixing the node and highlighting its connected edges.  
  - Hover over an anchor: Focus view (other nodes and edges fade to transparent).  

- **Canvas Mode**:  
  - Right-click and drag: Create a rectangular area.  
  - Double-click a rectangle: Edit the rectangle.  
  - Rectangles automatically align to nearby edges and their extensions.  

## Node Properties  
- **Title**  
- **External Image** (display the node as an image from an external link)  
- **Hyperlink** (a link icon appears; in Preview Mode, click to open)  

## Edge Properties  
- **Bidirectional relationship editing**  

## Rectangle Properties  
- **Tag assignment** (determines rectangle color and title)  

## Hotkeys  
- **A**: Default Mode  
- **W**: Connect Mode  
- **D**: Canvas Mode  
- **Shift**: Used with click/drag to fix nodes  
- **Q**: Search  
- **E**: Sidebar  

## URL Parameters  
- **Specify a JSON file**:  https://yourdomainname?**dataUrl=local-or-web-json-file**
- **Preview Mode**:  https://yourdomainname?dataUrl=local-or-web-json-file&**preview**(Displays the tag reference table and allows screenshot capture)
## Data Management  
- **One-click export** of the current graph as a JSON file.  
- **Save webpage as an image**:  
1. Enter **Preview Mode** and click the image icon in the upper-right corner.  
2. Press **F12** or **Ctrl + Shift + C** to open the browser’s developer tools.  
3. Adjust the view, then click the three-dot menu in the top-right of the preview interface.  
4. Select **Capture Screenshot** to save the image.  



# User Flows

## **_Users_**

-   Admin
-   General User:
    -   Potential Mural Client
    -   Art Viewer
    -   Art Buyer

<hr>

## **_User Objectives_**

### **Admin:**

_Managing Posts_

-   Add New Post
    -   (Personal CDN?)
-   Edit Post
-   Delete Post

_Managing Store_

-   Add New Item
-   Edit Item
-   Delete Item
-   See orders
-   See reporting records
-   Send "Item Shipped" email
    -   With/Without tracking info

_Managing Pages_

-   Edit Instagram Feed (General Art Page)
-   Edit "About me" section

### **General User:**

-   Browsing Mural/Art Posts
-   Browsing Store
-   Contact Page Owner (Artist)
-   Buying Item from store

<hr>

## **_User Flows_**

Key: [Starting Point] "Perform Action"

### **Admin:**

static _Admin Authentication_

1. [Login Screen]
2. "Login"
    - Forgot Password/Password Reset Screen

_Add New Post_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Posts Screen
4. Add New Post Screen
5. "Upload Image(s), Enter info"
6. "Submit"

_Edit Post_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Posts Screen
4. "Edit Post Button"
5. "Perform Edits"
6. "Submit"

_Delete Post_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Posts Screen
4. "Delete Post Button"
5. "Confirm"

_Add Store Item_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Store Management Screen
4. Edit Items Screen
5. "Add Item Button"
6. "Fill in info (name, description, price), upload image"

_Edit Store Item_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Store Management Screen
4. Edit Items Screen
5. "Edit Item Button"
6. "Edit info"
7. "Submit"

_Delte Store Item_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Store Management Screen
4. Edit Items Screen
5. "Delete Item Button"
6. "Confirm Button"

_View Store Orders_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Store Management Screen
4. Orders Page

    (Individual Item:)

5. "Click on individual item to view details"

_View Reporting_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Store Management Screen
4. Reporting Screen

_Update Order Status_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. Store Management Screen
4. Orders Page
5. "Click on item"
6. "Item Shipped Button"

_Edit General Art Page/IG Feed_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. "Edit Instagram Display Button"
4. IG Edit Screen
5. "Use radio buttons to select whether or not to show post"
6. "Save Button"

_Edit "About Me" Homepage_

1. [Admin Authentication]
2. Admin Dashboard Screen
3. "Edit Homescreen Button"
4. "Change info"
5. "Save Button"

### **General User**

_Browsing Mural/Art Posts_

1. [Homescreen / Landing Page]
2. "Murals Link"
3. "Individual mural link"
4. "General Art Link"
5. "Click general art post - takes them to IG post"

_Browsing Store_

1. [Homescreen / Landing Page]
2. "Store Link"
3. "Click through individual items"

_Contact Page Owner (Artist)_

1. [Homescreen / Landing Page]
2. "Contact Me Link"
3. "Fill out info"
4. "Submit"
5. (Receives Email Comment was Submitted)

_Buying Item from store_

1. [Homescreen / Landing Page]
2. "Store Link"
3. "Click to individual item"
4. "Buy Button"
5. "Fill out information"
6. "Fill out CC information"
7. "Submit"
8. (Receives email confirmation)

# **Lifecycle Page Usage Documentation**

## **1. Introduction**

The **Lifecycle Page** is designed to manage and track the lifecycle of crops within a polyhouse. It provides a comprehensive view of all ongoing, draft, and completed lifecycles, allowing users to monitor progress, update stages, and manage crop data effectively.

---

## **2. Features Overview**

- **List of Lifecycles**:
  - Displays all lifecycles created for a specific polyhouse.
  - Each card shows key details such as:
    - **Lifecycle Name** (e.g., "NLC-9").
    - **Crop Name** associated with the lifecycle.
    - **Quantity** of crops in the lifecycle.
    - **Current Step** of the lifecycle, indicating the stage currently in progress.
    - **Status** of the lifecycle (Draft, Running, or Completed).
- **Add New Lifecycle**:
  - Allows the creation of a new lifecycle for a specific polyhouse.
  - Users must specify:
    - **Lifecycle Name**.
    - **Crop**.
    - **Quantity**.
    - **Initial Stage** (e.g., Germination, Nursery, Vegetative, Flowering/Fruiting, Harvest).
- **Delete Lifecycle**:
  - Users can delete a lifecycle, but **only if its status is Draft**.

---

## **3. User Interface Guide**

### **Navigation**

- Access the Lifecycle page from the side menu under the "Life Cycles" section.
- Breadcrumb navigation is available at the top to help users identify their current position within the ERP.

### **Lifecycle Cards**

- Each card contains the following information:
  - **Lifecycle Name**: The unique identifier for the lifecycle (e.g., NLC-9).
  - **Crop**: The name of the crop assigned to this lifecycle (e.g., Basil, Broccoli).
  - **Quantity**: The number of crops included in this lifecycle.
  - **Current Step**: The stage the lifecycle is currently in (e.g., Germination, Harvest).
  - **Status**: The state of the lifecycle:
    - **Draft**: The lifecycle is created but not started.
    - **Running**: The lifecycle is active and progressing through stages.
    - **Completed**: The lifecycle is finished.

### **Action Buttons**

- **Add Lifecycle**: A button in the top-right corner to create a new lifecycle.
- **Delete**: Available for lifecycles in the **Draft** status.

---

## **4. How to Use the Lifecycle Page**

### **4.1 Viewing Lifecycles**

1. Navigate to the **Lifecycle Page**.
2. Browse through the cards to view details of each lifecycle.
   - Use the displayed crop name, quantity, and status to identify the lifecycle's progress.

### **4.2 Adding a New Lifecycle**

1. Click the **Add Lifecycle** button in the top-right corner.
2. Fill out the required details:
   - **Lifecycle Name**.
   - **Select Crop** from the dropdown.
   - **Enter Quantity** of crops.
   - **Select Initial Stage** (e.g., Germination, Nursery, Vegetative, Flowering/Fruiting, Harvest).
3. Save the lifecycle to add it to the list.

### **4.3 Deleting a Lifecycle**

1. Locate the lifecycle with the **Draft** status.
2. Click the **Delete** button.
3. Confirm the deletion. Note: Lifecycles in "Running" or "Completed" status cannot be deleted.

### **4.4 Managing Lifecycle Stages**

1. Locate the lifecycle card you want to update.
2. Review the **Current Step** displayed on the card.
3. Update the step or status as needed (e.g., move from "Germination" to "Harvest").

---

## **5. Status Explanations**

- **Draft**:
  - The lifecycle is saved but not yet started. Editable and deletable.
- **Running**:
  - The lifecycle is active. Users can update stages or track progress.
- **Completed**:
  - The lifecycle is finalized, indicating all stages are complete and locked for further edits.

---

## **6. Troubleshooting**

- **Lifecycle Not Displaying**:
  - Ensure the lifecycle is created for the correct polyhouse.
- **Unable to Update Lifecycle**:
  - Check if the lifecycle is in the "Completed" status, which makes it non-editable.

---

## **7. FAQs**

- **Q: Can I delete a running or completed lifecycle?**  
  **A:** No, lifecycles can only be deleted if they are in the **Draft** status.

- **Q: Can I change the initial stage after creating the lifecycle?**  
  **A:** No, the initial stage cannot be changed once the lifecycle is created. Please ensure the correct stage is selected during creation.

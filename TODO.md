# Testing Plan for News Section Edit Functionality

## Overview
Thorough testing of the inline edit functionality for the news section in admin.html, ensuring it matches the behavior of games, requirements, and descriptions sections.

## Steps to Complete

### 1. Launch Admin Panel
- [ ] Launch browser at http://localhost:8000/admin.html
- [ ] Verify admin panel loads correctly

### 2. Navigate to News Section
- [ ] Click on "Noticias" in the sidebar
- [ ] Verify news table loads with sample data

### 3. Test Inline Editing - Title Field
- [ ] Click on a news title cell to make it editable
- [ ] Edit the title text
- [ ] Click the save button (disk icon)
- [ ] Verify success notification appears
- [ ] Verify the change is reflected immediately

### 4. Test Inline Editing - Category Field
- [ ] Click on a category cell
- [ ] Edit the category text
- [ ] Save and verify change

### 5. Test Inline Editing - Author Field
- [ ] Click on author cell
- [ ] Edit author text
- [ ] Save and verify change

### 6. Test Inline Editing - Date Field
- [ ] Click on date cell
- [ ] Edit date text
- [ ] Save and verify change

### 7. Test Inline Editing - Views Field
- [ ] Click on views cell
- [ ] Edit views number
- [ ] Save and verify change

### 8. Test Inline Editing - Link Field
- [ ] Click on link cell
- [ ] Edit link text
- [ ] Save and verify change

### 9. Test Status Dropdown
- [ ] Change status from "Publicado" to "Borrador" using dropdown
- [ ] Verify change saves automatically
- [ ] Change back to "Publicado"
- [ ] Verify persistence

### 10. Test Data Persistence
- [ ] Reload the page
- [ ] Navigate back to news section
- [ ] Verify all edited changes are still present

### 11. Check Console for Errors
- [ ] Open browser developer tools
- [ ] Check console for any JavaScript errors during editing

### 12. Test Edge Cases
- [ ] Try saving with empty title field (should show error)
- [ ] Try saving with empty category field (should show error)
- [ ] Try saving with empty author field (should show error)
- [ ] Try saving with empty date field (should show error)
- [ ] Test with invalid views number (should default to 0)

### 13. Verify Integration
- [ ] Navigate to other sections (games, requirements, descriptions)
- [ ] Verify no conflicts or data corruption
- [ ] Return to news section and confirm data integrity

### 14. Final Verification
- [ ] Ensure UI consistency with other editable sections
- [ ] Confirm all functionality works as expected
- [ ] Close browser and complete testing

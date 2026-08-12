# lhl_omeka_upgrade

Some tips for a smooth transition

Update to "Browse Items" that displays Collection/Tags/Identifier 

file: /home/lhlphoto/public_html/admin/themes/default/javascripts/items-browse.js
Edit line 9 to disable auto-hiding of Details



<img width="654" height="550" alt="lhl_edit_to_show_details" src="https://github.com/user-attachments/assets/1cfcbc83-6b69-418b-9315-3bed0870d75d" />
// $('.details').hide();
        // edit... commented to make certain details section is not hidden (e.g., http://localhost/admin/items) -- bd 082724
        //

// edit... commented to make certain details section is not hidden (e.g., http://localhost/admin/items) -- bd 082724
// 

# The Remote Company Test
This is a test assignment for the product designer role for the remote company
## Figma Prototype Link
https://www.figma.com/proto/lFjVt8gDvT4MyK6WOWTmZZ/Resource-Management-App?page-id=0%3A1&node-id=7%3A9397&viewport=-13672%2C2461%2C0.59&scaling=scale-down&starting-point-node-id=7%3A9397

## Figma Design Link
https://www.figma.com/file/lFjVt8gDvT4MyK6WOWTmZZ/Resource-Management-App?node-id=0%3A1

## Design Decisions
### Admin Screen
For the Admin screen, I decided to go for a drag and drop uploader where the user can drag 1 or more files to upload or click on the box to choose files. 

When the user clicks on the upload box, the file browser opens. The user is able to select 1 or more images, pdfs, html, and/or zip files as per the brief. Other formats will be disabled so that the user cannot select incorrect format types.

After selecting the files and clicking on the 'Open' button on the file browser, the user will proceed to the Admin screen where a progress bar loader will display the name of the file the user is uploading and the progress of the upload until completion. 

If the user is uploading more than one file, instead of displaying the name of the file in the progress bar, the number of files that are being uploaded would display.

Once the file has finished uploading, the progress bar disappears and the notification bar confirms that the file was upload successfully. The user is able to dismiss the notification bar by clicking on the 'x' icon. 

Once the file/s have been uploaded, the table below the file uploader automatically reloads and the new files display first in the table. 

The table below the file uploader shows all the files that have been uploaded. It also shows the date of the upload and the size of each file. The admin is able to delete and download each file at any point. 

If the admin clicks on the delete icon, that prompts the user with a confirmation modal. The admin can cancel the action or proceed with the deletion by clicking Delete. Deleting the file will remove the file from the table in the UI. Once the file has been removed, the user will receive a confirmation message on a notification banner, stating that the file was deleted. The user is able to dismiss the notification bar by clicking on the 'x' icon. 

### Home Screen
As per the brief, the home screen displays all the files to the end user that were uploaded to the admin. 

For this screen I chose to display the files in a grid view, using thumbnails.

The user is able to click on each file to view the preview. The preview screen consists of the preview of the file on an overlay. At the top, the user can see the name of the file and perform a couple of actions such as download the file, go to the next file preview or go to the prevous file preview. The user can click on the background overlay to exit preview mode. 




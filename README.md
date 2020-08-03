# Rs_AOV_Transfer
A toolbar tool created to simplify the transfe of redshift AOV's from one ROP to another if you already have a set list of customized AOV's you don't wish to have to recreate.

NOTE: This tool was developed/tested with Redshift 3.0.1 for Houdini 18.0.480. It should work for other versions but if any of the AOV's names or variable names have changed then the tool will not be able to pick them up.


## Instalation:

After downloading, copy the .shelf files to this folder on your machine:

Windows: C:\Program Files\Side Effects Software\Houdini xx.x.xxx\houdini\toolbar

Mac: Libary/Frameworks/Houdini Framework/Versions/xx.x.xxx/Resources/hodini/toolbar (Note that I am unfamiliar with Mac and don't know if this path is correct)

Linux: /opt/hfs xx.x.xxx/houdini/toolbar

After restarting houdini the "MB_Shelf" should be avalible to add to your shelf tray by clicking the "+" button next to your shelves titles, hovering over the "Shelves" option and scrolling down to "MB_Shelf".

This is simply an empty shelf I have included where the tools can be placed. Feel free to make your own shelf or place my tools in one of the existing shelfs.

After selecting a shelf to place the tools in, right click on the shelf tab or on an empty part of the shelf and select "Edit shelf tab".
In the new window select the "Tools" tab and scroll down the list. All my tools are prefixed with "MB" so they should show up there.
Simply select the tool you want in the shelf and click "Apply" and then "Accept" and the tool should be ready for use.

## Usage:

Too use the tool simply click the shelf tool button, then select the rop to copy the AOV's from in the first pop-up, click accept, then select the ROP's to copy too in the next pop-up and finally click accept.

NOTE: This will only copy the actual values, it will not link multiple ROPs so any changes made in the future will not carry over.
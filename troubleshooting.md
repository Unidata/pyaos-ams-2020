This is a troubleshooting guide for issues you may run into while using <https://pyaos-workshop.unidata.ucar.edu>.


# Spawn Errors

Immediately after you log into <https://pyaos-workshop.unidata.ucar.edu> you may see a red error bar with a "spawn error" message or a "500" error. If you see this error, go to the "Home" menu "Start My Server" button. Occasionally, you have to do this a couple of times for your server to start.


# Notebooks Getting Stuck, Kernel Problems

When you open a notebook, a "kernel" is started on your behalf by Jupyter. The kernel provides the computing environment for your code to run and execute correctly. Jupyter will let you know the kernel is launching with a "Kernel starting, please wait&#x2026;" message in the menu bar area. There will also be an hourglass symbol in the browser tab title letting you know the kernel is starting. Sometimes the kernel can get stuck or not start at all. If this happens here are some steps you can try:

1.  Wait. Sometimes it takes a bit of time for a kernel to start, but it should not take more than a minute.
2.  Go to the "Kernel" menu and Interrupt or Restart the kernel.
3.  Close the notebook via the File ▶ Close and Halt menu item, and reopen the notebook.
4.  Repeat from step 1


# Updating the Workshop Material

The instructors may make last minute changes to the workshop material. In that case, the instructors may advise you to grab the latest instructional material. To achieve this, go to the "Home" menu and stop and start your server. Your local environment will now be up-to-date.


# Preserving Your Notebooks for After the Workshop

This is not a problem per se, but after the workshop is over, we will shutdown <https://pyaos-workshop.unidata.ucar.edu>. If you wish to save any work you have done during the workshop, please download your notebook via File ▶ "Download as" menu item. You will probably want to download the "Notebook .ipynb" option.


# Running Tab

In Jupyter, the "Running" tab lists which notebooks are running. Normally, you can shutdown your notebook in this tab, but unfortunately, the "Shutdown" button is currently broken. In your notebook, you can still shutdown your notebook via the Kernel ▶ Shutdown menu item. Alternatively, you can go to the Jupyter file navigation tree by clicking on the Jupyter logo in the upper-left part of your web page. Navigate to the notebook directory (pyaos-ams-2020 ▶ notebooks), select the running notebooks and click on the "Shutdown" button.

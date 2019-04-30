# Python_Toolbox_Final

Apache License 2.0

Made by Amy Wengefeld

4-30-2019

 This Python Toolbox contains 3 tools. The tools are MultipleBufferTool, ClipTool, and the
 SplitbyAttributeTool. They are designed to be used in that order. The MultipleBufferTool
 takes a point SHP file of well water workshops in RI (i.e. venues) and buffers them by 5, 10, 15,
 20, 150 miles. The output,Venues_MultipleRingBuffer_5, will be put into the input directory
 or GDB. Then the ClipTool clips, Venues_MultipleRingBuffer_5, to the RI_Boundary. The final tool,
 SplitbyAttributeTool, takes the previous output, Site_Buffer_clip, and splits the SHP file by
 their respective venues.
 
 The Zip_file, FINAL_CHALLENGE_TOOLBOX, contains 2 folders. 
 
      The folder, Final_Challenge_Data, contains a GDB named, "Python_TB_Challenge.gdb", which contains the example data.
      
      The folder, Toolbox_Challenge, contains the script and Python Toolbox.
    
 starter script was taken from
 http://desktop.arcgis.com/en/arcmap/10.3/analyze/creating-tools/a-quick-tour-of-python-toolboxes.htm

# Python_Toolbox_Final

# Made by Amy Wengefeld

# 4-30-2019

# This Python Toolbox contains 3 tools. The tools are MultipleBufferTool, ClipTool, and the
# SplitbyAttributeTool. They are designed to be used in that order. The MultipleBufferTool
# takes a point SHP file of well water workshops in RI (i.e. venues) and buffers them by 5, 10, 15,
# 20, 150 miles. The output,Venues_MultipleRingBuffer_5, will be put into the input directory
# or GDB. Then the ClipTool clips, Venues_MultipleRingBuffer_5, to the RI_Boundary. The final tool,
# SplitbyAttributeTool, takes the previous output, Site_Buffer_clip, and splits the SHP file by
# their respective venues.

# starter script was taken from
# http://desktop.arcgis.com/en/arcmap/10.3/analyze/creating-tools/a-quick-tour-of-python-toolboxes.htm

# Sudoku

Requirements -> Python, OpenCV, tensorflow 2.0, imageio

How to run the code:
  1) Download all the .ipynb file and make sure the digitrecognition.h5 file and input .mov file are in the same folder as the code.
  2) I ran this code on google colab and they use the command cv2_imshow instead of cv2.imshow, so at any point, if you do want to look at intermediate images, please keep this in      mind.
  3) On running the code step by step, the output video will be created in the same folder.
  

Sources:
  1) The original idea for this project came from -> https://www.youtube.com/watch?v=QR66rMS_ZfA&t=3s.
  2) The image preprocessing techniques came from the wonderful resources at pyimagesearch.com.
  3) The CNN model and architecture was taken directly from https://github.com/anhminhtran235. The function to center the images around the numbers which helped me boost my          accuracy also came from here.
  4) The sudoku puzzle was solved using a backtracking algorithm implemented here -> https://www.geeksforgeeks.org/sudoku-backtracking-7/.

# Image-Compression

  JPEG compression is a lossy image compression technique in which the compressed image suffers from quality loss. It provides the option of different quality speciications, where the quality of the compressed image is determined by comparing it with the original uncompressed image using a quantitative metric such as PSNR. For achieving different quality compressions, the discrete cosine transform (DCT) coefficients are divided by a quality map(determined by the user-speciied quality level). The DCT coefficients are real numbers, so I implemented JPEG compression using FP arithmetic in python.
  The image can be compressed at different quality level based on user requirement.

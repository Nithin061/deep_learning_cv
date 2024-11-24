# What is padding and why it is required?

    While doing the convolution operation to maintain the size of the o/p to be same as the input \
    we need to pad the pixels to the input image with zeros or near by pixel values.

    if input is n, kernel size k then o/p will be n-k+1 X n-k+1
    if input is n, kernel size k and with padding p then o/p will be n+2p-k+1 X n+2p-k+1

# What is stride and why it is required?

    While doing convolution operation we move the filter by default by 1 right and 1 down but you can configure it to be n

    if input is n, kernel size k and with padding p and stride s then o/p will be n+2p-k/s +1 X n+2p-k/s +1
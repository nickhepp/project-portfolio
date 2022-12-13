# CheezeWhiz
## Summary
A 360 degree spin photography capture software system that integrates multiple Canon DSLR cameras

### Technologies

Host application - Multi threaded .NET WinForms application with camera live view integration

Canon DSLR Integration - [Canon provided EOS SDK](https://developercommunity.usa.canon.com/canon) 

### Stage 1 - Setting the scene

Provides real time view for system operators to ensure cameras are aligned for proper angle and verify light settings are coorect: [Video of stage](https://drive.google.com/file/d/18QI0cW03i50G6mGi6_y33clPWhJFrNRa/view?usp=sharing)

### Stage 2 - Capturing the images

Shows progress bar through intuitive indicator to show which angles still need shots: [Video of stage](https://drive.google.com/file/d/18QI0cW03i50G6mGi6_y33clPWhJFrNRa/view?usp=sharing)

### Stage 3 - Post processing

During post processing, system operators get to crop and zoom images.  Single push button happens to publish 360 images: [Video of stage](https://drive.google.com/file/d/15PkColMMArgOU0Y3Gxs_9QlL_ukBP1jU/view?usp=share_link)

### Stage 4 - Publishing

Images are published via the background processes of the [media pipeline](./media_pipeline.md).




Farheen Gul and Masooma Bakhtiari (Simulations & Algorithm)
Amna Ehmer (Embedded Systems (Jetson Nano)) 
Irsa Aziz (Research & Development (Documentation & Life Cycle))
# Fog-removal-from-hazy-images
The project aims to develop an image enhancement framework that removes fog and haze from degraded images to improve object detection.

Overview and Motivation:
Vision based perception in hazy and foggy environments remains a significant bottleneck for
reliable deployment of object detection systems in real world scenarios. Traditional single image
dehazing methods although they are capable of improving perceptual visibility but often fail to
enhance and may even degrade downstream high level tasks due to their emphasis on low level
restoration metrics such as PSNR and SSIM. Recent studies increasingly argue that dehazing
must be rethought as a task driven or domain adaptive process that explicitly accounts for
detection robustness under adverse weather conditions. The emerging body of work can be
categorized into three converging lines of research: detection friendly dehazing, physics and
depth informed domain adaptation and joint dehazing detection optimization.
This project aims to develop to restore scene visibility degraded by atmospheric scattering, enabling
more reliable perception in outdoor environments. This task is critical for embedded systems
deployed in traffic monitoring, robotics, and autonomous platforms, where resource limited
hardware such as the Jetson Nano must operate in real time. Efficient, accurate dehazing
techniques balancing computational footprint and restoration quality are therefore of practical
importance.

We will be implementing CAP + an optimized FFA-Net on Jetson Nano which is appropriate and achievable for our
semester project. The tasks balance classical and deep learning methods allow meaningful
experimentation,and offer a publishable contribution. Furthermore, It is resource efficient
dehazing for embedded perception.

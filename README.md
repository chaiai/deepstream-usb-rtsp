# DeepStream 5.1 Python App for USB Camera feed to RTSP output stream

Follow directions in README for [deepstream_python_apps](https://github.com/NVIDIA-AI-IOT/deepstream_python_apps)

Find the correct dev node (/dev/video*) and capture formats with <code>v4l2-utils --list-devices</code>

Run with <code>python3 ./deepstream_usb_rtsp -c ds_usb_pgie_config.txt -i /dev/video0</code>

RTSP stream will be at rtsp://<NANO-IP-ADDRESS>:8554/ds-test

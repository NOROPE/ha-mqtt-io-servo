FROM homeassistant/armhf-base:latest
RUN pip3 install RPi.GPIO==0.7.1 mqtt-io
COPY mqtt_io_config.yaml /config/mqtt_io_config.yaml
CMD ["mqtt-io", "/config/mqtt_io_config.yaml"]
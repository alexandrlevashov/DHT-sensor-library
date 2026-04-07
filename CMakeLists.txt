
cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "DHT_U.cpp" "DHT.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES Adafruit_Sensor)

project(DHT-sensor-library)



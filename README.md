# Tikus Ultrasonic Industrial - Android APK

Android WebView wrapper for the Tikus Ultrasonic Industrial MQTT dashboard.

Default MQTT configuration:
- ESP32: broker.hivemq.com:1883
- App WebSocket: broker.hivemq.com:8884/mqtt (WSS)
- Base topic: servocontrol

The embedded UI communicates with the firmware using the firmware's exact MQTT contract:
- /command
- /config
- /tuning
- /control1
- /control2
- /auto
- /sensor
- /status

The APK does not use GPIO27 trigger pulse.

Build locally with Android Studio or run the included GitHub Actions workflow.

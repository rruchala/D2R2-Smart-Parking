Example file based on aws-iot-device-sdk-python-master example extended with sample_data.sson style messages

1. Download https://github.com/aws/aws-iot-device-sdk-python
2. Upload files from this example into samples/basicPubSub directory

3. Download device certificates from AWS
4. Start emulator using command style like:

python ../aws-iot-device-sdk-python-master/samples/basicPubSub/basicPubSubD2R2.py -e a64v33b9n6vca-ats.iot.eu-central-1.amazonaws.com -r AmazonRootCA1.pem -c da81520077-certificate.pem.crt -k da81520077-private.pem.key -t sensors/15275-Elfrieda-Street


# Modbus definitions for SDM630

This folder contains Home Assistant modbus definitions for an [Eastron SDM60-modbus V2](https://www.eastroneurope.com/products/view/sdm630modbus) kWh meter, connected through a Waveshare [Industrial RS232/RS485 to Ethernet Converter](https://www.waveshare.com/rs232-485-to-eth.htm) with the local network.

See the images for configuration details.

The provided yaml is set to work in `tcp` mode. If you want to use `rtuovertcp` (transparant mode), change the Work Mode of the converter from `TCP Server, ModbusTCP` to `TCP Server, None` and change `type: tcp` to `type: rtuovertcp` in the yaml.

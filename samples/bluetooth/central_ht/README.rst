.. _bluetooth_central_ht:

Bluetooth: Central / Health Thermometer sensor
##############################################

Overview
********

Similar to the :ref:`Central <bluetooth_central>` sample, except that this application specifically looks for multiple peripherals with health thermometer sensor and reports the
die temperature readings once connected.

It is possible to set the maximum number of peripheral connection to central. To achieve this, set the value for CONFIG_BT_MAX_CONN in prj.conf

Requirements
************

* BlueZ running on the host, or
* A board with BLE support

Building and Running
********************

This sample can be found under :zephyr_file:`samples/bluetooth/central_ht` in the
Zephyr tree.

See :ref:`bluetooth samples section <bluetooth-samples>` for details.

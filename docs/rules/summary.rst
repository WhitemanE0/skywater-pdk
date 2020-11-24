Summary of Key Periphery Rules
==============================

.. csv-table:: Table F3a: Front end layers (Low Voltage Devices)
   :file: summary/table-f3a-font-end-low-voltage.csv
   :header-rows: 1
   :stub-columns: 1

.. csv-table:: Table F3b: Front end layers (High Voltage Devices)
   :file: summary/table-f3b-font-end-high-voltage.csv
   :header-rows: 1
   :stub-columns: 1

Manual merge means that features below min. space should be manually merged by drawing.

.. csv-table:: Table F3c: Back end layers for S8D* flow
   :file: summary/table-f3c-back-end-high-S8Dx.csv
   :header-rows: 1
   :stub-columns: 1

.. csv-table:: Table F3d: Back end layers for S8T* flow
   :file: summary/table-f3d-back-end-high-S8Tx.csv
   :header-rows: 1
   :stub-columns: 1

.. csv-table:: Table F4: Connectivity of Drawn and Mask Layers [#f1]_
   :file: summary/table-f4-connectivity-of-drawn-and-mask.csv
   :header-rows: 1
   :stub-columns: 1

.. table-f4-key
.. rubric:: Footnotes

.. [#f1] All layers drawn except pmm which is created as cpmm:mask over bond pads or converted into cpbo:mask.
.. [#f2] Entries in this table show the layer (or combination of layers) that act as connecting layers listed in the row/column headings. An X indicates that there is no direct connection between these layers. N/A is entered along the diagonal. Over is entered along layers contacted by overlapping. A layer is always connected to itself.
.. [#f3] (Met5 AND pad AND rdl) should have one of the following sizes for LVS to work with WLCSP option: 60x60, 50x70, 60x80, and 80x80

.. csv-table:: Table F5: Device Connectivity Table
   :file: summary/table-f5-device-connectivity.csv
   :header-rows: 1
   :stub-columns: 1

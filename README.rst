PASCAL VOC Writer
=================

This library can be used to create image annotation XML files in the PASCAL VOC
file format.

Install
-------

``pip install pascal-voc-writer``

Use
---

.. code-block:: python
    writer = Writer('path/to/img.jpg', 800, 400)
    writer.addObject('cat', 100, 100, 200, 200)
    writer.save('path/to/img.xml')

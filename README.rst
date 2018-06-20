PASCAL VOC Writer
=================

This library can be used to create image annotation XML files in the PASCAL VOC
file format.

Install
-------

``pip install pascal-voc-writer``

Use
---

    from pascal_voc_writer import Writer

    # Writer(path, width, height)

    writer = Writer('path/to/img.jpg', 800, 400)


    # ::addObject(name, xmin, ymin, xmax, ymax)

    writer.addObject('cat', 100, 100, 200, 200)


    # ::save(path)

    writer.save('path/to/img.xml')

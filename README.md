rax_scheduled_images_python_novaclient_ext
==========================================

Nova client extension to the scheduled images Nova API extension

This extension is autodiscovered once installed. To use::

    pip install rax_scheduled_images_python_novaclient_ext

    nova scheduled-images-show <SERVER ID>
    nova scheduled-images-enable [--day-of-week <day>] <SERVER ID> <RETENTION>
        where day in ['sunday', 'monday', 'tuesday', 'wednesday',
                      'thursday', 'friday', 'saturday']
    nova scheduled-images-disable <SERVER ID>
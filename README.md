## massadmin

Mass updatting objects in Django's admin site.

## How to install

1. Add ```'massadmin'``` to ```INSTALLED_APPS``` in ```settings.py```
1. Add ```url(r'^admin/', include("massadmin.urls")),``` to ```urls.py BELOW url(r'^admin/', include(admin.site.urls)),```
1. Retranslate some russian words I've changed. I am too lazy to make MO files.

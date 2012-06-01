1 add 'filebrowser' in INSTALLED_APPS.

2 add url before admin urls:

    url(r'^admin/filebrowser/', include('filebrowser.urls')),

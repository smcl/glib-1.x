# glib-1.x

Making GLIB 1.x work with modern Linux systems, specifically so that I can build XMMS


# changes over base

1. updated config.sub && fixed gitignore
2. updated G_GNUC_PRETTY_FUNCTION - it's used without comma, causing compile error
3. moved g_bit_nth_msf, g_bit_nth_lsf and g_bit_nth_storage to gutils.c from glib.h
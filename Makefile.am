AM_CFLAGS =

AM_CPPFLAGS = \
	$(WARN_CFLAGS)	\
	-I.				\
	-I${includedir}

nx_camera_enc_LDADD =	\
	-lnx_video_api	\
	-lnx_v4l2

nx_camera_enc_SOURCES = \
	main.cpp

bin_PROGRAMS = nx_camera_enc

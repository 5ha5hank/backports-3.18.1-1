
saa7134-y +=	saa7134-cards.o saa7134-core.o saa7134-i2c.o
saa7134-y +=	saa7134-ts.o saa7134-tvaudio.o saa7134-vbi.o
saa7134-y +=	saa7134-video.o
saa7134-$(CPTCFG_VIDEO_SAA7134_RC) += saa7134-input.o

obj-$(CPTCFG_VIDEO_SAA7134) +=  saa7134.o saa7134-empress.o
obj-$(CPTCFG_VIDEO_SAA7134_GO7007) += saa7134-go7007.o

obj-$(CPTCFG_VIDEO_SAA7134_ALSA) += saa7134-alsa.o

obj-$(CPTCFG_VIDEO_SAA7134_DVB) += saa7134-dvb.o

ccflags-y += -I$(backport_srctree)/drivers/media/i2c
ccflags-y += -I$(backport_srctree)/drivers/media/tuners
ccflags-y += -I$(backport_srctree)/drivers/media/dvb-core
ccflags-y += -I$(backport_srctree)/drivers/media/dvb-frontends
ccflags-y += -I$(backport_srctree)/drivers/media/usb/go7007

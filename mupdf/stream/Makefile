TARGET_LIB=libstream.a
OBJS:=crypt_arc4.o crypt_crc32.o crypt_md5.o obj_array.o obj_dict.o obj_parse.o obj_print.o obj_simple.o
OBJS+=stm_buffer.o stm_filter.o stm_open.o stm_read.o stm_write.o stm_misc.o  filt_pipeline.o filt_arc4.o filt_null.o
OBJS+=filt_a85d.o filt_a85e.o filt_ahxd.o filt_ahxe.o filt_dctd.o filt_dcte.o  filt_faxd.o filt_faxdtab.o
OBJS+=filt_faxe.o filt_faxetab.o filt_flate.o filt_lzwd.o filt_lzwe.o filt_predict.o filt_rld.o filt_rle.o

INCDIR=../include
CFLAGS=-G0 -Wall -O2 -I/usr/local/pspdev/psp/include/freetype2
CXXFLAGS=$(CFLAGS) -fno-exceptions -fno-rtti -I/usr/local/pspdev/psp/include/freetype2
ASFLAGS=$(CFLAGS)

#EXTRA_TARGETS = EBOOT.PBP
#PSP_EBOOT_TITLE = Bookr - Book Reader

PSPSDK=$(shell psp-config --pspsdk-path)
#USE_PSPSDK_LIBC=1
include $(PSPSDK)/lib/build.mak



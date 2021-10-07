# GBA Template


## Setup

Default library is libgba, but to use libtonc instead, update the make file from:

```make
LIBS	:=  -lmm -lgba
LIBDIRS	:=	$(LIBGBA)
```

```make
LIBS	:=	-ltonc
LIBDIRS	:=	$(DEVKITPRO)/libtonc
```


ccflags-y := -Ofast -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -fsingle-precision-constant -mcpu=cortex-a9 -mtune=cortex-a9 -marm -mfpu=neon-vfpv4

obj-$(CONFIG_ION)       += ion.o ion_heap.o ion_page_pool.o ion_system_heap.o \
                                 ion_carveout_heap.o ion_chunk_heap.o ion_cma_heap.o
obj-$(CONFIG_ION_TEGRA) += tegra/
obj-$(CONFIG_ION_OMAP)  += omap/

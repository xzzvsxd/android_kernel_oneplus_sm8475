# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_GH_CTRL)		+= gh_ctrl.o
obj-$(CONFIG_GH_MSGQ)		+= gh_msgq.o
obj-$(CONFIG_GH_RM_DRV)		+= gh_rm_drv.o
gh_rm_drv-y 			:= gh_rm_core.o gh_rm_iface.o
obj-$(CONFIG_GH_DBL)		+= gh_dbl.o
obj-$(CONFIG_GH_IRQ_LEND)	+= gh_irq_lend.o
obj-$(CONFIG_GH_MEM_NOTIFIER)	+= gh_mem_notifier.o
obj-$(CONFIG_GH_VIRT_WATCHDOG)+= gh_virt_wdt.o
obj-$(CONFIG_GH_VIRTIO_BACKEND) += gh_virtio_backend.o
obj-$(CONFIG_GH_GUEST_POPS)	+= gh_guest_pops.o
obj-$(CONFIG_GH_VM_LOADER)	+= gh_vm_loader.o
gh_vm_loader-y			:= gh_vm_loader_core.o gh_vm_loader_sec.o

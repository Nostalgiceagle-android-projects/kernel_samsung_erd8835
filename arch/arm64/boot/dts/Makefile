# SPDX-License-Identifier: GPL-2.0
dtbo-y += exynos/board/erd/s5e8835-erd8835.dtbo
dtb-y += exynos/s5e8835.dtb
dtbo-y += samsung/a54x/a54x_eur_open_w00_r10.dtbo
dtbo-y += samsung/a54x/a54x_eur_open_w00_r05.dtbo
dtbo-y += samsung/a54x/a54x_eur_open_w00_r02.dtbo
dtbo-y += samsung/a54x/a54x_eur_open_w00_r03.dtbo
dtbo-y += samsung/a54x/a54x_eur_open_w00_r00.dtbo
dtbo-y += samsung/a54x/a54x_eur_open_w00_r01.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*

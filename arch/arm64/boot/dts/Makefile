# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos9825.dtb

dtbo-$(CONFIG_MODEL_D2S) += samsung/exynos9820-d2_eur_open_02.dtbo \
	samsung/exynos9820-d2_eur_open_16.dtbo \
	samsung/exynos9820-d2_eur_open_17.dtbo \
	samsung/exynos9820-d2_eur_open_18.dtbo \
	samsung/exynos9820-d2_eur_open_19.dtbo \
	samsung/exynos9820-d2_eur_open_20.dtbo \
	samsung/exynos9820-d2_eur_open_21.dtbo \
	samsung/exynos9820-d2_eur_open_22.dtbo \
	samsung/exynos9820-d2_eur_open_23.dtbo \
	samsung/exynos9820-d2_eur_open_24.dtbo

dtbo-$(CONFIG_MODEL_D1) += samsung/exynos9820-d1_eur_open_18.dtbo \
	samsung/exynos9820-d1_eur_open_19.dtbo \
	samsung/exynos9820-d1_eur_open_21.dtbo \
	samsung/exynos9820-d1_eur_open_22.dtbo \
	samsung/exynos9820-d1_eur_open_23.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*

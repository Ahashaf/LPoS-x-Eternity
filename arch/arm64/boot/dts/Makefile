# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos9820.dtb
dtb-y += exynos/exynos9825.dtb
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_17.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_18.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_19.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_20.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_22.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_24.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_eur_open_25.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_17.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_18.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_19.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_20.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_21.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_22.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_23.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_24.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_eur_open_26.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_04.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_16.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_17.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_18.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_19.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_20.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_23.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_24.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_25.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_eur_open_26.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_00.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_01.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_02.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_03.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_04.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_05.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_06.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_07.dtbo
dtbo-y += samsung/exynos9820-beyondx_eur_open_08.dtbo

#S10 5G KOR
dtbo-y += samsung/exynos9820-beyondx_kor_08.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_06.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_00.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_03.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_04.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_07.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_01.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_02.dtbo
dtbo-y += samsung/exynos9820-beyondx_kor_05.dtbo

#S10e KOR
dtbo-y += samsung/exynos9820-beyond0lte_kor_20.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_kor_19.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_kor_25.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_kor_18.dtbo
dtbo-y += samsung/exynos9820-beyond0lte_kor_17.dtbo

#S10 KOR
dtbo-y += samsung/exynos9820-beyond1lte_kor_21.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_kor_19.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_kor_26.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_kor_20.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_kor_17.dtbo
dtbo-y += samsung/exynos9820-beyond1lte_kor_18.dtbo

#S10+ KOR
dtbo-y += samsung/exynos9820-beyond2lte_kor_24.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_kor_26.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_kor_18.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_kor_20.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_kor_19.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_kor_17.dtbo
dtbo-y += samsung/exynos9820-beyond2lte_kor_25.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*

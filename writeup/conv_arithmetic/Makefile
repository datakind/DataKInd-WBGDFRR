conv_arithmetic.pdf : export BSTINPUTS=$BSTINPUTS:./natbib
conv_arithmetic.pdf : conv_arithmetic.tex
	pdflatex conv_arithmetic
	pdflatex conv_arithmetic
	bibtex conv_arithmetic
	pdflatex conv_arithmetic
	pdflatex conv_arithmetic

.PHONY : clean
clean : 
	rm -f conv_arithmetic.{aux,bbl,blg,log}

.PHONY : all_animations
all_animations : gif/full_padding_no_strides.gif gif/numerical_average_pooling.gif gif/same_padding_no_strides_transposed.gif gif/no_padding_strides_transposed.gif gif/arbitrary_padding_no_strides.gif gif/numerical_padding_strides.gif gif/arbitrary_padding_no_strides_transposed.gif gif/no_padding_no_strides.gif gif/padding_strides_odd.gif gif/no_padding_strides.gif gif/no_padding_no_strides_transposed.gif gif/dilation.gif gif/padding_strides_transposed.gif gif/numerical_max_pooling.gif gif/numerical_no_padding_no_strides.gif gif/padding_strides_odd_transposed.gif gif/full_padding_no_strides_transposed.gif gif/same_padding_no_strides.gif gif/padding_strides.gif

.SECONDARY : 

gif/full_padding_no_strides.gif : png/full_padding_no_strides_00.png png/full_padding_no_strides_01.png png/full_padding_no_strides_02.png png/full_padding_no_strides_03.png png/full_padding_no_strides_04.png png/full_padding_no_strides_05.png png/full_padding_no_strides_06.png png/full_padding_no_strides_07.png png/full_padding_no_strides_08.png png/full_padding_no_strides_09.png png/full_padding_no_strides_10.png png/full_padding_no_strides_11.png png/full_padding_no_strides_12.png png/full_padding_no_strides_13.png png/full_padding_no_strides_14.png png/full_padding_no_strides_15.png png/full_padding_no_strides_16.png png/full_padding_no_strides_17.png png/full_padding_no_strides_18.png png/full_padding_no_strides_19.png png/full_padding_no_strides_20.png png/full_padding_no_strides_21.png png/full_padding_no_strides_22.png png/full_padding_no_strides_23.png png/full_padding_no_strides_24.png png/full_padding_no_strides_25.png png/full_padding_no_strides_26.png png/full_padding_no_strides_27.png png/full_padding_no_strides_28.png png/full_padding_no_strides_29.png png/full_padding_no_strides_30.png png/full_padding_no_strides_31.png png/full_padding_no_strides_32.png png/full_padding_no_strides_33.png png/full_padding_no_strides_34.png png/full_padding_no_strides_35.png png/full_padding_no_strides_36.png png/full_padding_no_strides_37.png png/full_padding_no_strides_38.png png/full_padding_no_strides_39.png png/full_padding_no_strides_40.png png/full_padding_no_strides_41.png png/full_padding_no_strides_42.png png/full_padding_no_strides_43.png png/full_padding_no_strides_44.png png/full_padding_no_strides_45.png png/full_padding_no_strides_46.png png/full_padding_no_strides_47.png png/full_padding_no_strides_48.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/numerical_average_pooling.gif : png/numerical_average_pooling_00.png png/numerical_average_pooling_01.png png/numerical_average_pooling_02.png png/numerical_average_pooling_03.png png/numerical_average_pooling_04.png png/numerical_average_pooling_05.png png/numerical_average_pooling_06.png png/numerical_average_pooling_07.png png/numerical_average_pooling_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/same_padding_no_strides_transposed.gif : png/same_padding_no_strides_transposed_00.png png/same_padding_no_strides_transposed_01.png png/same_padding_no_strides_transposed_02.png png/same_padding_no_strides_transposed_03.png png/same_padding_no_strides_transposed_04.png png/same_padding_no_strides_transposed_05.png png/same_padding_no_strides_transposed_06.png png/same_padding_no_strides_transposed_07.png png/same_padding_no_strides_transposed_08.png png/same_padding_no_strides_transposed_09.png png/same_padding_no_strides_transposed_10.png png/same_padding_no_strides_transposed_11.png png/same_padding_no_strides_transposed_12.png png/same_padding_no_strides_transposed_13.png png/same_padding_no_strides_transposed_14.png png/same_padding_no_strides_transposed_15.png png/same_padding_no_strides_transposed_16.png png/same_padding_no_strides_transposed_17.png png/same_padding_no_strides_transposed_18.png png/same_padding_no_strides_transposed_19.png png/same_padding_no_strides_transposed_20.png png/same_padding_no_strides_transposed_21.png png/same_padding_no_strides_transposed_22.png png/same_padding_no_strides_transposed_23.png png/same_padding_no_strides_transposed_24.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/no_padding_strides_transposed.gif : png/no_padding_strides_transposed_00.png png/no_padding_strides_transposed_01.png png/no_padding_strides_transposed_02.png png/no_padding_strides_transposed_03.png png/no_padding_strides_transposed_04.png png/no_padding_strides_transposed_05.png png/no_padding_strides_transposed_06.png png/no_padding_strides_transposed_07.png png/no_padding_strides_transposed_08.png png/no_padding_strides_transposed_09.png png/no_padding_strides_transposed_10.png png/no_padding_strides_transposed_11.png png/no_padding_strides_transposed_12.png png/no_padding_strides_transposed_13.png png/no_padding_strides_transposed_14.png png/no_padding_strides_transposed_15.png png/no_padding_strides_transposed_16.png png/no_padding_strides_transposed_17.png png/no_padding_strides_transposed_18.png png/no_padding_strides_transposed_19.png png/no_padding_strides_transposed_20.png png/no_padding_strides_transposed_21.png png/no_padding_strides_transposed_22.png png/no_padding_strides_transposed_23.png png/no_padding_strides_transposed_24.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/arbitrary_padding_no_strides.gif : png/arbitrary_padding_no_strides_00.png png/arbitrary_padding_no_strides_01.png png/arbitrary_padding_no_strides_02.png png/arbitrary_padding_no_strides_03.png png/arbitrary_padding_no_strides_04.png png/arbitrary_padding_no_strides_05.png png/arbitrary_padding_no_strides_06.png png/arbitrary_padding_no_strides_07.png png/arbitrary_padding_no_strides_08.png png/arbitrary_padding_no_strides_09.png png/arbitrary_padding_no_strides_10.png png/arbitrary_padding_no_strides_11.png png/arbitrary_padding_no_strides_12.png png/arbitrary_padding_no_strides_13.png png/arbitrary_padding_no_strides_14.png png/arbitrary_padding_no_strides_15.png png/arbitrary_padding_no_strides_16.png png/arbitrary_padding_no_strides_17.png png/arbitrary_padding_no_strides_18.png png/arbitrary_padding_no_strides_19.png png/arbitrary_padding_no_strides_20.png png/arbitrary_padding_no_strides_21.png png/arbitrary_padding_no_strides_22.png png/arbitrary_padding_no_strides_23.png png/arbitrary_padding_no_strides_24.png png/arbitrary_padding_no_strides_25.png png/arbitrary_padding_no_strides_26.png png/arbitrary_padding_no_strides_27.png png/arbitrary_padding_no_strides_28.png png/arbitrary_padding_no_strides_29.png png/arbitrary_padding_no_strides_30.png png/arbitrary_padding_no_strides_31.png png/arbitrary_padding_no_strides_32.png png/arbitrary_padding_no_strides_33.png png/arbitrary_padding_no_strides_34.png png/arbitrary_padding_no_strides_35.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/numerical_padding_strides.gif : png/numerical_padding_strides_00.png png/numerical_padding_strides_01.png png/numerical_padding_strides_02.png png/numerical_padding_strides_03.png png/numerical_padding_strides_04.png png/numerical_padding_strides_05.png png/numerical_padding_strides_06.png png/numerical_padding_strides_07.png png/numerical_padding_strides_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/arbitrary_padding_no_strides_transposed.gif : png/arbitrary_padding_no_strides_transposed_00.png png/arbitrary_padding_no_strides_transposed_01.png png/arbitrary_padding_no_strides_transposed_02.png png/arbitrary_padding_no_strides_transposed_03.png png/arbitrary_padding_no_strides_transposed_04.png png/arbitrary_padding_no_strides_transposed_05.png png/arbitrary_padding_no_strides_transposed_06.png png/arbitrary_padding_no_strides_transposed_07.png png/arbitrary_padding_no_strides_transposed_08.png png/arbitrary_padding_no_strides_transposed_09.png png/arbitrary_padding_no_strides_transposed_10.png png/arbitrary_padding_no_strides_transposed_11.png png/arbitrary_padding_no_strides_transposed_12.png png/arbitrary_padding_no_strides_transposed_13.png png/arbitrary_padding_no_strides_transposed_14.png png/arbitrary_padding_no_strides_transposed_15.png png/arbitrary_padding_no_strides_transposed_16.png png/arbitrary_padding_no_strides_transposed_17.png png/arbitrary_padding_no_strides_transposed_18.png png/arbitrary_padding_no_strides_transposed_19.png png/arbitrary_padding_no_strides_transposed_20.png png/arbitrary_padding_no_strides_transposed_21.png png/arbitrary_padding_no_strides_transposed_22.png png/arbitrary_padding_no_strides_transposed_23.png png/arbitrary_padding_no_strides_transposed_24.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/no_padding_no_strides.gif : png/no_padding_no_strides_00.png png/no_padding_no_strides_01.png png/no_padding_no_strides_02.png png/no_padding_no_strides_03.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/padding_strides_odd.gif : png/padding_strides_odd_00.png png/padding_strides_odd_01.png png/padding_strides_odd_02.png png/padding_strides_odd_03.png png/padding_strides_odd_04.png png/padding_strides_odd_05.png png/padding_strides_odd_06.png png/padding_strides_odd_07.png png/padding_strides_odd_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/no_padding_strides.gif : png/no_padding_strides_00.png png/no_padding_strides_01.png png/no_padding_strides_02.png png/no_padding_strides_03.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/no_padding_no_strides_transposed.gif : png/no_padding_no_strides_transposed_00.png png/no_padding_no_strides_transposed_01.png png/no_padding_no_strides_transposed_02.png png/no_padding_no_strides_transposed_03.png png/no_padding_no_strides_transposed_04.png png/no_padding_no_strides_transposed_05.png png/no_padding_no_strides_transposed_06.png png/no_padding_no_strides_transposed_07.png png/no_padding_no_strides_transposed_08.png png/no_padding_no_strides_transposed_09.png png/no_padding_no_strides_transposed_10.png png/no_padding_no_strides_transposed_11.png png/no_padding_no_strides_transposed_12.png png/no_padding_no_strides_transposed_13.png png/no_padding_no_strides_transposed_14.png png/no_padding_no_strides_transposed_15.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/dilation.gif : png/dilation_00.png png/dilation_01.png png/dilation_02.png png/dilation_03.png png/dilation_04.png png/dilation_05.png png/dilation_06.png png/dilation_07.png png/dilation_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/padding_strides_transposed.gif : png/padding_strides_transposed_00.png png/padding_strides_transposed_01.png png/padding_strides_transposed_02.png png/padding_strides_transposed_03.png png/padding_strides_transposed_04.png png/padding_strides_transposed_05.png png/padding_strides_transposed_06.png png/padding_strides_transposed_07.png png/padding_strides_transposed_08.png png/padding_strides_transposed_09.png png/padding_strides_transposed_10.png png/padding_strides_transposed_11.png png/padding_strides_transposed_12.png png/padding_strides_transposed_13.png png/padding_strides_transposed_14.png png/padding_strides_transposed_15.png png/padding_strides_transposed_16.png png/padding_strides_transposed_17.png png/padding_strides_transposed_18.png png/padding_strides_transposed_19.png png/padding_strides_transposed_20.png png/padding_strides_transposed_21.png png/padding_strides_transposed_22.png png/padding_strides_transposed_23.png png/padding_strides_transposed_24.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/numerical_max_pooling.gif : png/numerical_max_pooling_00.png png/numerical_max_pooling_01.png png/numerical_max_pooling_02.png png/numerical_max_pooling_03.png png/numerical_max_pooling_04.png png/numerical_max_pooling_05.png png/numerical_max_pooling_06.png png/numerical_max_pooling_07.png png/numerical_max_pooling_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/numerical_no_padding_no_strides.gif : png/numerical_no_padding_no_strides_00.png png/numerical_no_padding_no_strides_01.png png/numerical_no_padding_no_strides_02.png png/numerical_no_padding_no_strides_03.png png/numerical_no_padding_no_strides_04.png png/numerical_no_padding_no_strides_05.png png/numerical_no_padding_no_strides_06.png png/numerical_no_padding_no_strides_07.png png/numerical_no_padding_no_strides_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/padding_strides_odd_transposed.gif : png/padding_strides_odd_transposed_00.png png/padding_strides_odd_transposed_01.png png/padding_strides_odd_transposed_02.png png/padding_strides_odd_transposed_03.png png/padding_strides_odd_transposed_04.png png/padding_strides_odd_transposed_05.png png/padding_strides_odd_transposed_06.png png/padding_strides_odd_transposed_07.png png/padding_strides_odd_transposed_08.png png/padding_strides_odd_transposed_09.png png/padding_strides_odd_transposed_10.png png/padding_strides_odd_transposed_11.png png/padding_strides_odd_transposed_12.png png/padding_strides_odd_transposed_13.png png/padding_strides_odd_transposed_14.png png/padding_strides_odd_transposed_15.png png/padding_strides_odd_transposed_16.png png/padding_strides_odd_transposed_17.png png/padding_strides_odd_transposed_18.png png/padding_strides_odd_transposed_19.png png/padding_strides_odd_transposed_20.png png/padding_strides_odd_transposed_21.png png/padding_strides_odd_transposed_22.png png/padding_strides_odd_transposed_23.png png/padding_strides_odd_transposed_24.png png/padding_strides_odd_transposed_25.png png/padding_strides_odd_transposed_26.png png/padding_strides_odd_transposed_27.png png/padding_strides_odd_transposed_28.png png/padding_strides_odd_transposed_29.png png/padding_strides_odd_transposed_30.png png/padding_strides_odd_transposed_31.png png/padding_strides_odd_transposed_32.png png/padding_strides_odd_transposed_33.png png/padding_strides_odd_transposed_34.png png/padding_strides_odd_transposed_35.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/full_padding_no_strides_transposed.gif : png/full_padding_no_strides_transposed_00.png png/full_padding_no_strides_transposed_01.png png/full_padding_no_strides_transposed_02.png png/full_padding_no_strides_transposed_03.png png/full_padding_no_strides_transposed_04.png png/full_padding_no_strides_transposed_05.png png/full_padding_no_strides_transposed_06.png png/full_padding_no_strides_transposed_07.png png/full_padding_no_strides_transposed_08.png png/full_padding_no_strides_transposed_09.png png/full_padding_no_strides_transposed_10.png png/full_padding_no_strides_transposed_11.png png/full_padding_no_strides_transposed_12.png png/full_padding_no_strides_transposed_13.png png/full_padding_no_strides_transposed_14.png png/full_padding_no_strides_transposed_15.png png/full_padding_no_strides_transposed_16.png png/full_padding_no_strides_transposed_17.png png/full_padding_no_strides_transposed_18.png png/full_padding_no_strides_transposed_19.png png/full_padding_no_strides_transposed_20.png png/full_padding_no_strides_transposed_21.png png/full_padding_no_strides_transposed_22.png png/full_padding_no_strides_transposed_23.png png/full_padding_no_strides_transposed_24.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/same_padding_no_strides.gif : png/same_padding_no_strides_00.png png/same_padding_no_strides_01.png png/same_padding_no_strides_02.png png/same_padding_no_strides_03.png png/same_padding_no_strides_04.png png/same_padding_no_strides_05.png png/same_padding_no_strides_06.png png/same_padding_no_strides_07.png png/same_padding_no_strides_08.png png/same_padding_no_strides_09.png png/same_padding_no_strides_10.png png/same_padding_no_strides_11.png png/same_padding_no_strides_12.png png/same_padding_no_strides_13.png png/same_padding_no_strides_14.png png/same_padding_no_strides_15.png png/same_padding_no_strides_16.png png/same_padding_no_strides_17.png png/same_padding_no_strides_18.png png/same_padding_no_strides_19.png png/same_padding_no_strides_20.png png/same_padding_no_strides_21.png png/same_padding_no_strides_22.png png/same_padding_no_strides_23.png png/same_padding_no_strides_24.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

gif/padding_strides.gif : png/padding_strides_00.png png/padding_strides_01.png png/padding_strides_02.png png/padding_strides_03.png png/padding_strides_04.png png/padding_strides_05.png png/padding_strides_06.png png/padding_strides_07.png png/padding_strides_08.png
	convert -delay 100 -loop 0 -layers Optimize +map -dispose previous $^ $@
	gifsicle --batch -O3 $@

png/%.png : pdf/%.pdf
	convert -density 600 $< -flatten -resize 25% $@

pdf/full_padding_no_strides_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 0 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 1 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 2 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 3 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 4 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 5 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 6 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 7 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 8 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 9 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 10 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 11 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 12 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 13 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 14 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 15 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 16 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 17 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 18 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 19 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 20 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 21 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 22 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 23 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 24 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_25.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 25 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_26.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 26 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_27.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 27 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_28.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 28 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_29.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 29 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_30.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 30 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_31.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 31 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_32.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 32 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_33.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 33 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_34.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 34 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_35.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 35 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_36.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 36 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_37.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 37 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_38.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 38 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_39.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 39 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_40.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 40 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_41.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 41 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_42.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 42 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_43.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 43 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_44.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 44 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_45.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 45 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_46.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 46 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_47.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 47 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/full_padding_no_strides_48.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides 48 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 

pdf/numerical_average_pooling_00.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 0 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_01.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 1 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_02.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 2 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_03.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 3 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_04.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 4 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_05.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 5 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_06.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 6 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_07.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 7 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/numerical_average_pooling_08.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_average_pooling 8 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=average 

pdf/same_padding_no_strides_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 0 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 1 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 2 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 3 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 4 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 5 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 6 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 7 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 8 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 9 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 10 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 11 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 12 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 13 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 14 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 15 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 16 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 17 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 18 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 19 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 20 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 21 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 22 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 23 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_transposed_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides_transposed 24 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_strides_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 0 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 1 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 2 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 3 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 4 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 5 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 6 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 7 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 8 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 9 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 10 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 11 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 12 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 13 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 14 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 15 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 16 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 17 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 18 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 19 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 20 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 21 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 22 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 23 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/no_padding_strides_transposed_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides_transposed 24 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 --transposed

pdf/arbitrary_padding_no_strides_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 0 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 1 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 2 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 3 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 4 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 5 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 6 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 7 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 8 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 9 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 10 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 11 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 12 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 13 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 14 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 15 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 16 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 17 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 18 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 19 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 20 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 21 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 22 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 23 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 24 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_25.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 25 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_26.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 26 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_27.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 27 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_28.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 28 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_29.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 29 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_30.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 30 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_31.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 31 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_32.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 32 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_33.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 33 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_34.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 34 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/arbitrary_padding_no_strides_35.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides 35 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 

pdf/numerical_padding_strides_00.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 0 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_01.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 1 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_02.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 2 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_03.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 3 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_04.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 4 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_05.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 5 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_06.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 6 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_07.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 7 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/numerical_padding_strides_08.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_padding_strides 8 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --mode=convolution 

pdf/arbitrary_padding_no_strides_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 0 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 1 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 2 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 3 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 4 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 5 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 6 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 7 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 8 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 9 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 10 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 11 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 12 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 13 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 14 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 15 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 16 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 17 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 18 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 19 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 20 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 21 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 22 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 23 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/arbitrary_padding_no_strides_transposed_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic arbitrary_padding_no_strides_transposed 24 --input-size=5 --output-size=6 --padding=2 --kernel-size=4 --stride=1 --transposed

pdf/no_padding_no_strides_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides 0 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 

pdf/no_padding_no_strides_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides 1 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 

pdf/no_padding_no_strides_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides 2 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 

pdf/no_padding_no_strides_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides 3 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 

pdf/padding_strides_odd_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 0 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 1 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 2 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 3 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 4 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 5 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 6 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 7 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_odd_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd 8 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/no_padding_strides_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides 0 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 

pdf/no_padding_strides_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides 1 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 

pdf/no_padding_strides_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides 2 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 

pdf/no_padding_strides_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_strides 3 --input-size=5 --output-size=2 --padding=0 --kernel-size=3 --stride=2 

pdf/no_padding_no_strides_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 0 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 1 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 2 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 3 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 4 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 5 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 6 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 7 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 8 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 9 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 10 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 11 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 12 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 13 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 14 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/no_padding_no_strides_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic no_padding_no_strides_transposed 15 --input-size=4 --output-size=2 --padding=0 --kernel-size=3 --stride=1 --transposed

pdf/dilation_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 0 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 1 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 2 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 3 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 4 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 5 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 6 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 7 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/dilation_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic dilation 8 --input-size=7 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --dilation=2 

pdf/padding_strides_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 0 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 1 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 2 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 3 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 4 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 5 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 6 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 7 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 8 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 9 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 10 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 11 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 12 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 13 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 14 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 15 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 16 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 17 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 18 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 19 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 20 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 21 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 22 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 23 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_transposed_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_transposed 24 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/numerical_max_pooling_00.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 0 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_01.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 1 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_02.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 2 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_03.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 3 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_04.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 4 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_05.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 5 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_06.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 6 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_07.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 7 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_max_pooling_08.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_max_pooling 8 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=max 

pdf/numerical_no_padding_no_strides_00.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 0 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_01.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 1 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_02.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 2 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_03.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 3 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_04.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 4 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_05.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 5 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_06.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 6 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_07.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 7 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/numerical_no_padding_no_strides_08.pdf : bin/produce_figure templates/numerical_figure.txt
	./bin/produce_figure numerical numerical_no_padding_no_strides 8 --input-size=5 --output-size=3 --padding=0 --kernel-size=3 --stride=1 --mode=convolution 

pdf/padding_strides_odd_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 0 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 1 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 2 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 3 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 4 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 5 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 6 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 7 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 8 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 9 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 10 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 11 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 12 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 13 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 14 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 15 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 16 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 17 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 18 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 19 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 20 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 21 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 22 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 23 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 24 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_25.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 25 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_26.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 26 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_27.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 27 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_28.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 28 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_29.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 29 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_30.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 30 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_31.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 31 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_32.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 32 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_33.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 33 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_34.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 34 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/padding_strides_odd_transposed_35.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides_odd_transposed 35 --input-size=6 --output-size=3 --padding=1 --kernel-size=3 --stride=2 --transposed

pdf/full_padding_no_strides_transposed_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 0 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 1 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 2 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 3 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 4 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 5 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 6 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 7 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 8 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 9 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 10 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 11 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 12 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 13 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 14 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 15 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 16 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 17 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 18 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 19 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 20 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 21 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 22 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 23 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/full_padding_no_strides_transposed_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic full_padding_no_strides_transposed 24 --input-size=5 --output-size=7 --padding=2 --kernel-size=3 --stride=1 --transposed

pdf/same_padding_no_strides_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 0 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 1 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 2 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 3 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 4 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 5 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 6 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 7 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 8 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_09.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 9 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_10.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 10 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_11.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 11 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_12.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 12 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_13.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 13 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_14.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 14 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_15.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 15 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_16.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 16 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_17.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 17 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_18.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 18 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_19.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 19 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_20.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 20 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_21.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 21 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_22.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 22 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_23.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 23 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/same_padding_no_strides_24.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic same_padding_no_strides 24 --input-size=5 --output-size=5 --padding=1 --kernel-size=3 --stride=1 

pdf/padding_strides_00.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 0 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_01.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 1 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_02.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 2 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_03.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 3 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_04.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 4 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_05.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 5 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_06.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 6 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_07.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 7 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

pdf/padding_strides_08.pdf : bin/produce_figure templates/arithmetic_figure.txt templates/unit.txt
	./bin/produce_figure arithmetic padding_strides 8 --input-size=5 --output-size=3 --padding=1 --kernel-size=3 --stride=2 

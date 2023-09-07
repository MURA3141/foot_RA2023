Ageing <br>
> data <- matrix(c( 6, 2, 14,25, 5, 211, 536, 1445, 1786, 532 ), ncol = 2)<br>
> rownames(data) <- c("Row1", "Row2", "Row3", "Row4", "Row5")<br>
> colnames(data) <- c("Col1", "Col2")<br>
> print(data)<br>
> test_result <- fisher.test(data)<br>
> print(test_result)<br>
>
sex<br>
>  data <- matrix(c(48,3,4230,264 ), ncol = 2)<br>
>  rownames(data) <- c("Row1", "Row2")<br>
>  colnames(data) <- c("Col1", "Col2")<br>
>  print(data)<br>
>  test_result <- fisher.test(data)<br>
>  print(test_result)<br>


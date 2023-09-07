Ageing 
> data <- matrix(c( 6, 2, 14,25, 5, 211, 536, 1445, 1786, 532 ), ncol = 2)
> rownames(data) <- c("Row1", "Row2", "Row3", "Row4", "Row5")
> colnames(data) <- c("Col1", "Col2")
> print(data)
> test_result <- fisher.test(data)
> print(test_result)
>
>  data <- matrix(c(48,3,4230,264 ), ncol = 2)
>  rownames(data) <- c("Row1", "Row2")
>  colnames(data) <- c("Col1", "Col2")
>  print(data)
>  test_result <- fisher.test(data)
>  print(test_result)


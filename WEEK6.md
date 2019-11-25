## 图1
**代码**：  
> ggplot(crime, aes(x = year, y = percent, fill = item)) +geom_col(position = "dodge", colour = "black") +
scale_fill_manual(breaks = c("广东省未成年犯父亲受教育程度（初中及以下）", "国民男性受教育程度（初中及以下）", 
"广东省未成年犯母亲受教育程度（初中及以下）", "国民女性受教育程度（初中及以下）"),  
values=c("#03A9F4", "#81D4FA", "#FF8A65", "#FFCC80")) + ggtitle("广东省未成年犯父母受教育程度")

## 图2
**代码**：
> pie.sales <- c(0.707,0.072, 0.123, 0.98)
> names(pie.sales) <- c("farmer/workman", "Unemployed", "Self employed", "Cadres/soldiers/technicians")
> pie.col <- c("#303F9F", "#3A6BBC", "#4597DA", "#4FC3F7")
> pie.sales <- sort(pie.sales, decreasing = TRUE)
> pie(pie.sales, col = pie.col)

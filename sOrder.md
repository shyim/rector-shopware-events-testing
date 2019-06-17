# sOrder

# [filter] [Shopware_Modules_Order_GetOrdernumber_FilterOrdernumber](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L249)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |


# [filter] [Shopware_Modules_Order_SaveOrder_FilterParams](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L614)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |


# [filter] [Shopware_Modules_Order_SaveOrder_FilterAttributes](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L656)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| orderID        | PHPStan\Type\IntegerType           |
| orderParams        | PHPStan\Type\MixedType           |


# [filter] [Shopware_Modules_Order_SaveOrder_FilterDetailsSQL](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L720)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| row        | PHPStan\Type\ArrayType           |
| user        | PHPStan\Type\ArrayType           |
| order        | PHPStan\Type\Constant\ConstantArrayType           |


# [filter] [Shopware_Modules_Order_SaveOrder_FilterDetailAttributes](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L754)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| basketRow        | PHPStan\Type\ArrayType           |
| orderdetailsID        | PHPStan\Type\IntegerType           |


# [filter] [Shopware_Modules_Order_SendMail_FilterVariables](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L868)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |


# [filter] [Shopware_Modules_Order_SendMail_FilterContext](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L926)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |


# [filter] [Shopware_Modules_Order_SendMail_Filter](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L954)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| context        | PHPStan\Type\MixedType           |
| variables        | PHPStan\Type\MixedType           |


# [filter] [Shopware_Modules_Order_SaveBilling_FilterSQL](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1047)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| address        | PHPStan\Type\ArrayType           |
| id        | PHPStan\Type\IntegerType           |


# [filter] [Shopware_Modules_Order_SaveBilling_FilterArray](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1072)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| address        | PHPStan\Type\ArrayType           |
| id        | PHPStan\Type\IntegerType           |


# [filter] [Shopware_Modules_Order_SaveShipping_FilterSQL](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1153)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| address        | PHPStan\Type\ArrayType           |
| id        | PHPStan\Type\IntegerType           |


# [filter] [Shopware_Modules_Order_SaveShipping_FilterArray](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1176)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| address        | PHPStan\Type\ArrayType           |
| id        | PHPStan\Type\IntegerType           |


# [filter] [Shopware_Controllers_Backend_OrderState_Filter](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1368)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\UnionType           |
| id        | PHPStan\Type\IntegerType           |
| status        | PHPStan\Type\IntegerType           |
| mailname        | PHPStan\Type\StringType           |
| mail        | PHPStan\Type\ObjectType           |
| engine        | PHPStan\Type\UnionType           |
# [notify] [Shopware_Modules_Order_SaveOrder_ProcessDetails](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L789)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| details        | PHPStan\Type\MixedType           |
| orderId        | PHPStan\Type\IntegerType           |


# [notify] [Shopware_Modules_Order_SendMail_BeforeSend](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L964)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| mail        | PHPStan\Type\ObjectType           |
| context        | PHPStan\Type\MixedType           |
| variables        | PHPStan\Type\MixedType           |


# [notify] [Shopware_Controllers_Backend_OrderState_Send_BeforeSend](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1252)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\UnionType           |
| mail        | PHPStan\Type\ObjectType           |


# [notify] [Shopware_Controllers_Backend_OrderState_Notify](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1347)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\UnionType           |
| id        | PHPStan\Type\IntegerType           |
| status        | PHPStan\Type\IntegerType           |
| mailname        | PHPStan\Type\StringType           |


# [notify] [product_stock_was_changed](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L1876)

## Parameters
| Name        | Type           |
| number        | PHPStan\Type\StringType           |
| quantity        | PHPStan\Type\IntegerType           |
# [notifyUntil] [Shopware_Modules_Order_SendMail_Create](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L933)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| context        | PHPStan\Type\MixedType           |
| variables        | PHPStan\Type\MixedType           |


# [notifyUntil] [Shopware_Modules_Order_SendMail_Send](https://github.com/shopware/shopware/blob/5.6/engine/Shopware/Core/sOrder.php#L974)

## Parameters
| Name        | Type           |
| subject        | PHPStan\Type\ThisType           |
| mail        | PHPStan\Type\ObjectType           |
| context        | PHPStan\Type\MixedType           |
| variables        | PHPStan\Type\MixedType           |

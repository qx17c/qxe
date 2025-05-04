### [👉👉👉♥♥点此进入♥观看入口👈👈👈](https://mrddrm.github.io/app.html)
<br></br><br></br><br></br>
def display_products(self):
        """显示所有可购买的商品"""
        print("\n=== 可乐自动贩卖机 ===")
        print("商品列表:")
        for i, (name, info) in enumerate(self.products.items(), 1):
            print(f"{i}. {name} - ¥{info['price']} (库存: {info['stock']})")
        print("=" * 20)
    
    def insert_coin(self, coin):
        """插入硬币"""
        if coin not in self.coins:
            print(f"错误: 无法识别面额 ¥{coin} 的硬币")
            return False

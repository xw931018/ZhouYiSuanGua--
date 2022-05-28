# ZhouYiSuanGua--
一个简易的模拟大衍揲蓍法算卦的小notebook。以大衍之数，蓍草为媒，诚心问卜，引而伸之，触类而长之，天下之能事毕矣

This is a simple toy peoject motivated by one of the most ancient Chinese devination, I Ching, or translated as 'The Book of Changes'.

I Ching was originally  manuscripted more than 2500 years ago (1000-700 BC), used by our ancestors to tell the fortune. 

According to Wikipedia: 

"The I Ching or Yi Jing (Chinese: 易經, Mandarin: [î tɕíŋ] (listen)), usually translated as Book of Changes or Classic of Changes, is an ancient Chinese divination text and among the oldest of the Chinese classics. Originally a divination manual in the Western Zhou period (1000–750 BC), the I Ching was transformed over the course of the Warring States and early imperial periods (500–200 BC) into a cosmological text with a series of philosophical commentaries known as the "Ten Wings".[1] After becoming part of the Five Classics in the 2nd century BC, the I Ching was the subject of scholarly commentary and the basis for divination practice for centuries across the Far East, and eventually took on an influential role in Western understanding of Eastern thought.[2]

As a divination text, the I Ching is used for a traditional Chinese form of cleromancy known as I Ching divination, in which bundles of yarrow stalks are manipulated to produce sets of six apparently random numbers ranging from 6 to 9. Each of the 64 possible sets corresponds to a hexagram, which can be looked up in the text. The hexagrams are arranged in an order known as the King Wen sequence. The interpretation of the readings found in the I Ching is a matter which has been endlessly discussed and debated over in the centuries following its compilation, and many commentators have used the book symbolically, often to provide guidance for moral decision making as informed by Confucianism, Taoism and Buddhism. The hexagrams themselves have often acquired cosmological significance and been paralleled with many other traditional names for the processes of change such as yin and yang and Wu Xing."

This jupyter notebook simulate the process of generating 6 I numbers which was orinally practiced with certain type of herb in real life scenario. Running this notebook, you will obtain a ordered set of 6 'Yao', either Yao of Yin (denoted by - -) or Yao of Yang (denoted by ——). This ordered set is called 'Gua'(卦). Note that Yin/Yang is a concept in Chinese philosophy signifying relativity and changes. Yin represents feminin/lunar concepts while Yang represents masculin/solar concepts. There are in total 2^6=64 possible combination of Yaos, hence 64 different possible 'Gua's you can get.

After you obtain a 'Gua', you would then need to refer to I Ching for a interpretation of this 'Gua', such as what the 6 'Yao's at their positions means and what aspects you would need to pay attention to, conditioned on current 'Gua'. Currently this interpretation is beyond the scope of this notebook. But I will try to incorporate a i Ching databse which can interpret automatically every 'Gua' you obtain, 'in the future'...

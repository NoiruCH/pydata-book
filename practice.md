
# 14章演習問題
所与の条件を以下に記載する

## 1. ドメイン取得分析
dataset = 'datasets/bitly_usagov/example.txt'

1. タイムゾーンの割合
2. タイムゾーンにおけるWindows使用割合

## 2. 映画リコメンド
dataset = 'datasets/movielens/users.dat'
    names = ['user_id', 'gender', 'age', 'occupation', 'zip'], sep='::'
dataset = 'datasets/movielens/ratings.dat'
    names = ['user_id', 'movie_id', 'rating', 'timestamp'], sep='::'
dataset = 'datasets/movielens/movies.dat'
    names = ['movie_id', 'title', 'genres'], sep='::'

1. 映画ごとの男女による平均値の算出
2. 男女間でレビュー点数に乖離があったものの調査

## 3. 新生児名前図鑑
dataset = 'datasets/babynames/yob1880.txt'
dataset = 'datasets/babynames/yob2019.txt'
    names = ['name', 'gender', 'births'], sep=','

1. 年度ごとの男女別出生数
2. ポピュラーな名前の分析、使用率の推移
3. 男女ごとの名前の多様性の変遷
4. 末尾文字使用率の算出

## 4. 食糧DB
dataset = 'datasets/usda_food/database.json'

1. 任意の栄養素における食品群の含有量の平均値
2. 任意の栄養素における含有量が最も高い食品群の調査

## 5. 2012年大統領選結果
dataset = 'datasets/fec/P00000001-ALL.csv'

1. 職業ごとの支持政党割合（民主党 or 共和党）
2. 寄付金額ごとに分析
3. 州ごとに分析


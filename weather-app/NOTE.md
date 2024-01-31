# Steps

## 步骤一：

### 按照职责划分组件，用功能去命名

#### 思路一

- WeatherApp
    - WeatherCard
        - CurrentCity
            - Image
            - MainDetails
            - Icon
            - OtherDetails
        - Forecast
            - DayOfWeek
                - Date
                - Icon
                - TemperatureRange
                - Week
        - SearchBar
        - SearchHistory


## 步骤二：

### 构建一个静态版本

- 公共组件 （为什么要复用）
    - TemperatureRange

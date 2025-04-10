# This Repo is to Store Data-s

## Data Structure 資料結構

This repository contains real estate transaction data for Taipei City (TP) and New Taipei City (NTP). The data is categorized into sales, pre-construction sales, and rental properties, with both detailed transaction records and district-level average price summaries.

本資料庫包含臺北市(TP)和新北市(NTP)的不動產交易資料。資料分為買賣、預售屋買賣和租賃三大類，並包含詳細交易紀錄及各行政區平均地價摘要。

### File Naming Convention 檔案命名規則

- **TP**: Taipei City 臺北市
- **NTP**: New Taipei City 新北市

### Data Categories 資料類別

1. **Sales Data 不動產買賣**
   - `TP_Sales.csv`: Taipei City Property Sales 臺北市不動產買賣
   - `NTP_Sales.csv`: New Taipei City Property Sales 新北市不動產買賣

2. **Pre-Construction Sales Data 預售屋買賣**
   - `TP_PreConSales.csv`: Taipei City Pre-Construction Sales 臺北市預售屋買賣
   - `NTP_PreConSales.csv`: New Taipei City Pre-Construction Sales 新北市預售屋買賣

3. **Rental Data 不動產租賃**
   - `TP_Rentals.csv`: Taipei City Property Rentals 臺北市不動產租賃
   - `NTP_Rentals.csv`: New Taipei City Property Rentals 新北市不動產租賃

### District Average Price Summaries 各行政區平均地價摘要

These files contain aggregated average prices by district for each category:
以下檔案包含各類別依行政區統計的平均價格：

1. **Sales Average Price 買賣平均價格**
   - `TP_Sales_AvgPrice_District.csv`: Taipei City Districts
   - `NTP_Sales_AvgPrice_District.csv`: New Taipei City Districts

2. **Pre-Construction Sales Average Price 預售屋平均價格**
   - `TP_PreConSales_AvgPrice_District.csv`: Taipei City Districts
   - `NTP_PreConSales_AvgPrice_District.csv`: New Taipei City Districts

3. **Rental Average Price 租賃平均價格**
   - `TP_Rentals_AvgPrice_District.csv`: Taipei City Districts
   - `NTP_Rentals_AvgPrice_District.csv`: New Taipei City Districts

## Note on Large Files 大型檔案說明

Some data files exceed 100MB and are handled using Git LFS (Large File Storage):
部分資料檔案超過100MB，使用Git LFS (Large File Storage)進行管理：

- `NTP_Sales.csv` (296MB)
- `TP_Sales.csv` (130MB)

Please ensure you have Git LFS installed when cloning this repository.
請確保在克隆此儲存庫時已安裝Git LFS。

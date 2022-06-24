# QUANTAXIS财务指标中英文对照表

< TOC>

- [QUANTAXIS财务指标中英文对照表](#quantaxis财务指标中英文对照表)
    - [0.注意](#0注意)
    - [1.每股指标](#1每股指标)
    - [2. 资产负债表 BALANCE SHEET](#2-资产负债表-balance-sheet)
        - [2.1 资产](#21-资产)
            - [2.1.1 流动资产](#211-流动资产)
            - [2.1.2 非流动资产](#212-非流动资产)
        - [2.2 负债](#22-负债)
            - [2.2.1 流动负债](#221-流动负债)
            - [2.2.2 非流动负债](#222-非流动负债)
        - [2.3 所有者权益](#23-所有者权益)
    - [3. 利润表](#3-利润表)
    - [4. 现金流量表](#4-现金流量表)
        - [4.1 经营活动 Operating](#41-经营活动-operating)
        - [4.2 投资活动 Investment](#42-投资活动-investment)
        - [4.3 筹资活动 Financing](#43-筹资活动-financing)
        - [4.4 汇率变动](#44-汇率变动)
        - [4.5 现金及现金等价物净增加](#45-现金及现金等价物净增加)
        - [4.6 期末现金及现金等价物余额](#46-期末现金及现金等价物余额)
        - [4.x 补充项目 Supplementary Schedule：](#4x-补充项目-supplementary-schedule)
            - [现金流量附表项目    Indirect Method](#现金流量附表项目----indirect-method)
            - [4.x.1 将净利润调节为经营活动现金流量 Convert net profit to cash flow from operating activities](#4x1-将净利润调节为经营活动现金流量-convert-net-profit-to-cash-flow-from-operating-activities)
            - [4.x.2 不涉及现金收支的投资和筹资活动 Investing and financing activities not involved in cash](#4x2-不涉及现金收支的投资和筹资活动-investing-and-financing-activities-not-involved-in-cash)
            - [4.x.3 现金及现金等价物净增加情况 Net increase of cash and cash equivalents](#4x3-现金及现金等价物净增加情况-net-increase-of-cash-and-cash-equivalents)
    - [5. 偿债能力分析](#5-偿债能力分析)
    - [6. 经营效率分析](#6-经营效率分析)
    - [7. 发展能力分析](#7-发展能力分析)
    - [8. 获利能力分析](#8-获利能力分析)
    - [9. 资本结构分析](#9-资本结构分析)
    - [10. 现金流量分析](#10-现金流量分析)
    - [11. 单季度财务指标](#11-单季度财务指标)
    - [12.股本股东](#12股本股东)
    - [13.机构持股](#13机构持股)
    - [14.新增指标](#14新增指标)

< /TOC>

## 0.注意

该部分需要配合 QUANTAXIS CLI的 save financialfiles 使用

## 1.每股指标

'001基本每股收益': 'EPS',

'002扣除非经常性损益每股收益': 'deductEPS',

'003每股未分配利润': 'undistributedProfitPerShare',

'004每股净资产': 'netAssetsPerShare',

'005每股资本公积金': 'capitalReservePerShare',

'006净资产收益率': 'ROE',

'007每股经营现金流量': 'operatingCashFlowPerShare',

## 2. 资产负债表 BALANCE SHEET
### 2.1 资产
#### 2.1.1 流动资产

'008货币资金': 'moneyFunds',

'009交易性金融资产': 'tradingFinancialAssets',

'010应收票据': 'billsReceivables',

'011应收账款': 'accountsReceivables',

'012预付款项': 'prepayments',

'013其他应收款': 'otherReceivables',

'014应收关联公司款': 'interCompanyReceivables',

'015应收利息': 'interestReceivables',

'016应收股利': 'dividendsReceivables',

'017存货': 'inventory',

'018其中：消耗性生物资产': 'expendableBiologicalAssets',

'019一年内到期的非流动资产': 'noncurrentAssetsDueWithinOneYear',

'020其他流动资产': 'otherLiquidAssets',

'021流动资产合计': 'totalLiquidAssets',

#### 2.1.2 非流动资产
'022可供出售金融资产': 'availableForSaleSecurities',

'023持有至到期投资': 'heldToMaturityInvestments',

'024长期应收款': 'longTermReceivables',

'025长期股权投资': 'longTermEquityInvestment',

'026投资性房地产': 'investmentRealEstate',

'027固定资产': 'fixedAssets',

'028在建工程': 'constructionInProgress',

'029工程物资': 'engineerMaterial',

'030固定资产清理': 'fixedAssetsCleanUp',

'031生产性生物资产': 'productiveBiologicalAssets',

'032油气资产': 'oilAndGasAssets',

'033无形资产': 'intangibleAssets',

'034开发支出': 'developmentExpenditure',

'035商誉': 'goodwill',

'036长期待摊费用': 'longTermDeferredExpenses',

'037递延所得税资产': 'deferredIncomeTaxAssets',

'038其他非流动资产': 'otherNonCurrentAssets',

'039非流动资产合计': 'totalNonCurrentAssets',

'040资产总计': 'totalAssets',

### 2.2 负债
#### 2.2.1 流动负债

'041短期借款': 'shortTermLoan',

'042交易性金融负债': 'tradingFinancialLiabilities',

'043应付票据': 'billsPayable',

'044应付账款': 'accountsPayable',

'045预收款项': 'advancedReceivable',

'046应付职工薪酬': 'employeesPayable',

'047应交税费': 'taxPayable',

'048应付利息': 'interestPayable',

'049应付股利': 'dividendPayable',

'050其他应付款': 'otherPayable',

'051应付关联公司款': 'interCompanyPayable',

'052一年内到期的非流动负债': 'noncurrentLiabilitiesDueWithinOneYear',

'053其他流动负债': 'otherCurrentLiabilities',

'054流动负债合计': 'totalCurrentLiabilities',

#### 2.2.2 非流动负债

'055长期借款': 'longTermLoans',

'056应付债券': 'bondsPayable',

'057长期应付款': 'longTermPayable',

'058专项应付款': 'specialPayable',

'059预计负债': 'estimatedLiabilities',

'060递延所得税负债': 'defferredIncomeTaxLiabilities',

'061其他非流动负债': 'otherNonCurrentLiabilities',

'062非流动负债合计': 'totalNonCurrentLiabilities',

'063负债合计': 'totalLiabilities',

### 2.3 所有者权益

'064实收资本（或股本）': 'totalShare',

'065资本公积': 'capitalReserve',

'066盈余公积': 'surplusReserve',

'067减：库存股': 'treasuryStock',

'068未分配利润': 'undistributedProfits',

'069少数股东权益': 'minorityEquity',

'070外币报表折算价差': 'foreignCurrencyReportTranslationSpread',

'071非正常经营项目收益调整': 'abnormalBusinessProjectEarningsAdjustment',

'072所有者权益（或股东权益）合计': 'totalOwnersEquity',

'073负债和所有者（或股东权益）合计': 'totalLiabilitiesAndOwnersEquity',

## 3. 利润表

'074其中：营业收入': 'operatingRevenue',

'075其中：营业成本': 'operatingCosts',

'076营业税金及附加': 'taxAndSurcharges',

'077销售费用': 'salesCosts',

'078管理费用': 'managementCosts',

'079堪探费用': 'explorationCosts',

'080财务费用': 'financialCosts',

'081资产减值损失': 'assestsDevaluation',

'082加：公允价值变动净收益': 'profitAndLossFromFairValueChanges',

'083投资收益': 'investmentIncome',

'084其中：对联营企业和合营企业的投资收益': 'investmentIncomeFromAffiliatedBusinessAndCooperativeEnterprise',

'085影响营业利润的其他科目': 'otherSubjectsAffectingOperatingProfit',

'086三、营业利润': 'operatingProfit',

'087加：补贴收入': 'subsidyIncome',

'088营业外收入': 'nonOperatingIncome',

'089减：营业外支出': 'nonOperatingExpenses',

'090其中：非流动资产处置净损失': 'netLossFromDisposalOfNonCurrentAssets',

'091加：影响利润总额的其他科目': 'otherSubjectsAffectTotalProfit',

'092四、利润总额': 'totalProfit',

'093减：所得税': 'incomeTax',

'094加：影响净利润的其他科目': 'otherSubjectsAffectNetProfit',

'095五、净利润': 'netProfit',

'096归属于母公司所有者的净利润': 'netProfitsBelongToParentCompanyOwner',

'097少数股东损益': 'minorityProfitAndLoss',

## 4. 现金流量表
### 4.1 经营活动 Operating

'098销售商品、提供劳务收到的现金': 'cashFromGoodsSalesorOrRenderingOfServices',

'099收到的税费返还': 'refundOfTaxAndFeeReceived',

'100收到其他与经营活动有关的现金': 'otherCashRelatedBusinessActivitiesReceived',

'101经营活动现金流入小计': 'cashInflowsFromOperatingActivities',

'102购买商品、接受劳务支付的现金': 'buyingGoodsReceivingCashPaidForLabor',

'103支付给职工以及为职工支付的现金': 'paymentToEmployeesAndCashPaidForEmployees',

'104支付的各项税费': 'paymentsOfVariousTaxes',

'105支付其他与经营活动有关的现金': 'paymentOfOtherCashRelatedToBusinessActivities',

'106经营活动现金流出小计': 'cashOutflowsFromOperatingActivities',

'107经营活动产生的现金流量净额': 'netCashFlowsFromOperatingActivities',

### 4.2 投资活动 Investment

'108收回投资收到的现金': 'cashReceivedFromInvestmentReceived',

'109取得投资收益收到的现金': 'cashReceivedFromInvestmentIncome',

'110处置固定资产、无形资产和其他长期资产收回的现金净额': 'disposalOfNetCashForRecoveryOfFixedAssetsIntangibleAssetsAndOtherLongTermAssets',

'111处置子公司及其他营业单位收到的现金净额': 'disposalOfNetCashReceivedFromSubsidiariesAndOtherBusinessUnits',

'112收到其他与投资活动有关的现金': 'otherCashReceivedRelatingToInvestingActivities',

'113投资活动现金流入小计': 'cashinFlowsFromInvestmentActivities',

'114购建固定资产、无形资产和其他长期资产支付的现金': 'cashForThePurchaseConstructionPaymentOfFixedAssetsIntangibleAssetsAndOtherLongTermAssets',

'115投资支付的现金': 'cashInvestment',

'116取得子公司及其他营业单位支付的现金净额': 'acquisitionOfNetCashPaidBySubsidiariesAndOtherBusinessUnits',

'117支付其他与投资活动有关的现金': 'otherCashPaidRelatingToInvestingActivities',

'118投资活动现金流出小计': 'cashOutflowsFromInvestmentActivities',

'119投资活动产生的现金流量净额': 'netCashFlowsFromInvestingActivities',

### 4.3 筹资活动 Financing

'120吸收投资收到的现金': 'cashReceivedFromInvestors',

'121取得借款收到的现金': 'cashFromBorrowings',

'122收到其他与筹资活动有关的现金': 'otherCashReceivedRelatingToFinancingActivities',

'123筹资活动现金流入小计': 'cashInflowsFromFinancingActivities',

'124偿还债务支付的现金': 'cashPaymentsOfAmountBorrowed',

'125分配股利、利润或偿付利息支付的现金': 'cashPaymentsForDistrbutionOfDividendsOrProfits',

'126支付其他与筹资活动有关的现金': 'otherCashPaymentRelatingToFinancingActivities',

'127筹资活动现金流出小计': 'cashOutflowsFromFinancingActivities',

'128筹资活动产生的现金流量净额': 'netCashFlowsFromFinancingActivities',

### 4.4 汇率变动

'129四、汇率变动对现金的影响': 'effectOfForeignExchangRateChangesOnCash',

'130四(2)、其他原因对现金的影响': 'effectOfOtherReasonOnCash',

### 4.5 现金及现金等价物净增加

'131五、现金及现金等价物净增加额': 'netIncreaseInCashAndCashEquivalents',

'132期初现金及现金等价物余额': 'initialCashAndCashEquivalentsBalance',

### 4.6 期末现金及现金等价物余额

'133期末现金及现金等价物余额': 'theFinalCashAndCashEquivalentsBalance',

### 4.x 补充项目 Supplementary Schedule：
#### 现金流量附表项目    Indirect Method
#### 4.x.1 将净利润调节为经营活动现金流量 Convert net profit to cash flow from operating activities

'134净利润': 'netProfitFromOperatingActivities',

'135资产减值准备': 'provisionForAssetsLosses',

'136固定资产折旧、油气资产折耗、生产性生物资产折旧': 'depreciationForFixedAssets',

'137无形资产摊销': 'amortizationOfIntangibleAssets',

'138长期待摊费用摊销': 'amortizationOfLong-termDeferredExpenses',

'139处置固定资产、无形资产和其他长期资产的损失': 'lossOfDisposingFixedAssetsIntangibleAssetsAndOtherLong-termAssets',

'140固定资产报废损失': 'scrapLossOfFixedAssets',

'141公允价值变动损失': 'lossFromFairValueChange',

'142财务费用': 'financialExpenses',

'143投资损失': 'investmentLosses',

'144递延所得税资产减少': 'decreaseOfDeferredTaxAssets',

'145递延所得税负债增加': 'increaseOfDeferredTaxLiabilities',

'146存货的减少': 'decreaseOfInventory',

'147经营性应收项目的减少': 'decreaseOfOperationReceivables',

'148经营性应付项目的增加': 'increaseOfOperationPayables',

'149其他': 'others',

'150经营活动产生的现金流量净额2': 'netCashFromOperatingActivities2',

#### 4.x.2 不涉及现金收支的投资和筹资活动 Investing and financing activities not involved in cash

'151债务转为资本': 'debtConvertedToCSapital',

'152一年内到期的可转换公司债券': 'convertibleBondMaturityWithinOneYear',

'153融资租入固定资产': 'leaseholdImprovements',

#### 4.x.3 现金及现金等价物净增加情况 Net increase of cash and cash equivalents

'154现金的期末余额': 'cashEndingBal',

'155现金的期初余额': 'cashBeginingBal',

'156现金等价物的期末余额': 'cashEquivalentsEndingBal',

'157现金等价物的期初余额': 'cashEquivalentsBeginningBal',

'158现金及现金等价物净增加额': 'netIncreaseOfCashAndCashEquivalents',

## 5. 偿债能力分析

'159流动比率': 'currentRatio',  # 流动资产/流动负债

'160速动比率': 'acidTestRatio',  # (流动资产-存货）/流动负债

'161现金比率(%)': 'cashRatio',  # (货币资金+有价证券)÷流动负债

'162利息保障倍数': 'interestCoverageRatio',  # (利润总额+财务费用（仅指利息费用部份）)/利息费用

'163非流动负债比率(%)': 'noncurrentLiabilitiesRatio',

'164流动负债比率(%)': 'currentLiabilitiesRatio',

'165现金到期债务比率(%)': 'cashDebtRatio',  # 企业经营现金净流入/(本期到期长期负债+本期应付票据)

'166有形资产净值债务率(%)': 'debtToTangibleAssetsRatio',

'167权益乘数(%)': 'equityMultiplier',  # 资产总额/股东权益总额

'168股东的权益/负债合计(%)': 'equityDebtRatio',  # 权益负债率

'169有形资产/负债合计(%)': 'tangibleAssetDebtRatio ',  # 有形资产负债率

'170经营活动产生的现金流量净额/负债合计(%)': 'netCashFlowsFromOperatingActivitiesDebtRatio',

'171EBITDA/负债合计(%)': 'EBITDA/Liabilities',

## 6. 经营效率分析

""" 销售收入÷平均应收账款=销售收入\(0.5 x(应收账款期初+期末))"""

'172应收帐款周转率': 'turnoverRatioOfReceivable;',

'173存货周转率': 'turnoverRatioOfInventory',

"""(存货周转天数+应收帐款周转天数-应付帐款周转天数+预付帐款周转天数-预收帐款周转天数)/365"""

'174运营资金周转率': 'turnoverRatioOfOperatingAssets',

'175总资产周转率': 'turnoverRatioOfTotalAssets',

'176固定资产周转率': 'turnoverRatioOfFixedAssets',  # 企业销售收入与固定资产净值的比率

'177应收帐款周转天数': 'daysSalesOutstanding',  # 企业从取得应收账款的权利到收回款项、转换为现金所需要的时间

'178存货周转天数': 'daysSalesOfInventory',  # 企业从取得存货开始，至消耗、销售为止所经历的天数

'179流动资产周转率': 'turnoverRatioOfCurrentAssets',  # 流动资产周转率(次)=主营业务收入/平均流动资产总额

'180流动资产周转天数': 'daysSalesofCurrentAssets',

'181总资产周转天数': 'daysSalesofTotalAssets',

'182股东权益周转率': 'equityTurnover',  # 销售收入/平均股东权益

## 7. 发展能力分析

'183营业收入增长率(%)': 'operatingIncomeGrowth',

'184净利润增长率(%)': 'netProfitGrowthRate',  # NPGR  利润总额－所得税

'185净资产增长率(%)': 'netAssetsGrowthRate',

'186固定资产增长率(%)': 'fixedAssetsGrowthRate',

'187总资产增长率(%)': 'totalAssetsGrowthRate',

'188投资收益增长率(%)': 'investmentIncomeGrowthRate',

'189营业利润增长率(%)': 'operatingProfitGrowthRate',

'190暂无': 'None1',

'191暂无': 'None2',

'192暂无': 'None3',

## 8. 获利能力分析

'193成本费用利润率(%)': 'rateOfReturnOnCost',

'194营业利润率': 'rateOfReturnOnOperatingProfit',

'195营业税金率': 'rateOfReturnOnBusinessTax',

'196营业成本率': 'rateOfReturnOnOperatingCost',

'197净资产收益率': 'rateOfReturnOnCommonStockholdersEquity',

'198投资收益率': 'rateOfReturnOnInvestmentIncome',

'199销售净利率(%)': 'rateOfReturnOnNetSalesProfit',

'200总资产报酬率': 'rateOfReturnOnTotalAssets',

'201净利润率': 'netProfitMargin',

'202销售毛利率(%)': 'rateOfReturnOnGrossProfitFromSales',

'203三费比重': 'threeFeeProportion',

'204管理费用率': 'ratioOfChargingExpense',

'205财务费用率': 'ratioOfFinancialExpense',

'206扣除非经常性损益后的净利润': 'netProfitAfterExtraordinaryGainsAndLosses',

'207息税前利润(EBIT)': 'EBIT',

'208息税折旧摊销前利润(EBITDA)': 'EBITDA',

'209EBITDA/营业总收入(%)': 'EBITDA/GrossRevenueRate',

## 9. 资本结构分析

'210资产负债率(%)': 'assetsLiabilitiesRatio',

'211流动资产比率': 'currentAssetsRatio',

'212货币资金比率': 'monetaryFundRatio',

'213存货比率': 'inventoryRatio',

'214固定资产比率': 'fixedAssetsRatio',

'215负债结构比': 'liabilitiesStructureRatio',

'216归属于母公司股东权益/全部投入资本(%)': 'shareholdersOwnershipOfAParentCompany/TotalCapital',

'217股东的权益/带息债务(%)': 'shareholdersInterest/InterestRateDebtRatio',

'218有形资产/净债务(%)': 'tangibleAssets/NetDebtRatio',

## 10. 现金流量分析

'219每股经营性现金流(元)': 'operatingCashFlowPerShare',

'220营业收入现金含量(%)': 'cashOfOperatingIncome',

'221经营活动产生的现金流量净额/经营活动净收益(%)': 'netOperatingCashFlow/netOperationProfit',

'222销售商品提供劳务收到的现金/营业收入(%)': 'cashFromGoodsSales/OperatingRevenue',

'223经营活动产生的现金流量净额/营业收入': 'netOperatingCashFlow/OperatingRevenue',

'224资本支出/折旧和摊销': 'capitalExpenditure/DepreciationAndAmortization',

'225每股现金流量净额(元)': 'netCashFlowPerShare',

'226经营净现金比率（短期债务）': 'operatingCashFlow/ShortTermDebtRatio',

'227经营净现金比率（全部债务）': 'operatingCashFlow/LongTermDebtRatio',

'228经营活动现金净流量与净利润比率': 'cashFlowRateAndNetProfitRatioOfOperatingActivities',

'229全部资产现金回收率': 'cashRecoveryForAllAssets',

## 11. 单季度财务指标

'230营业收入': 'operatingRevenueSingle',

'231营业利润': 'operatingProfitSingle',

'232归属于母公司所有者的净利润': 'netProfitBelongingToTheOwnerOfTheParentCompanySingle',

'233扣除非经常性损益后的净利润': 'netProfitAfterExtraordinaryGainsAndLossesSingle',

'234经营活动产生的现金流量净额': 'netCashFlowsFromOperatingActivitiesSingle',

'235投资活动产生的现金流量净额': 'netCashFlowsFromInvestingActivitiesSingle',

'236筹资活动产生的现金流量净额': 'netCashFlowsFromFinancingActivitiesSingle',

'237现金及现金等价物净增加额': 'netIncreaseInCashAndCashEquivalentsSingle',

## 12.股本股东

'238总股本': 'totalCapital',

'239已上市流通A股': 'listedAShares',

'240已上市流通B股': 'listedBShares',

'241已上市流通H股': 'listedHShares',

'242股东人数(户)': 'numberOfShareholders',

'243第一大股东的持股数量': 'theNumberOfFirstMajorityShareholder',

'244十大流通股东持股数量合计(股)': 'totalNumberOfTopTenCirculationShareholders',

'245十大股东持股数量合计(股)': 'totalNumberOfTopTenMajorShareholders',

## 13.机构持股

'246机构总量（家）': 'institutionNumber',

'247机构持股总量(股)': 'institutionShareholding',

'248QFII机构数': 'QFIIInstitutionNumber',

'249QFII持股量': 'QFIIShareholding',

'250券商机构数': 'brokerNumber',

'251券商持股量': 'brokerShareholding',

'252保险机构数': 'securityNumber',

'253保险持股量': 'securityShareholding',

'254基金机构数': 'fundsNumber',

'255基金持股量': 'fundsShareholding',

'256社保机构数': 'socialSecurityNumber',

'257社保持股量': 'socialSecurityShareholding',

'258私募机构数': 'privateEquityNumber',

'259私募持股量': 'privateEquityShareholding',

'260财务公司机构数': 'financialCompanyNumber',

'261财务公司持股量': 'financialCompanyShareholding',

'262年金机构数': 'pensionInsuranceAgencyNumber',

'263年金持股量': 'pensionInsuranceAgencyShareholfing',

## 14.新增指标

""" [注：季度报告中，若股东同时持有非流通A股性质的股份(如同时持有流通A股和流通B股），取的是包含同时持有非流通A股性质的流通股数]"""

'264十大流通股东中持有A股合计(股)': 'totalNumberOfTopTenCirculationShareholders',

'265第一大流通股东持股量(股)': 'firstLargeCirculationShareholdersNumber',

""" [注：1.自由流通股=已流通A股-十大流通股东5%以上的A股；2.季度报告中，若股东同时持有非流通A股性质的股份(如同时持有流通A股和流通H股），5%以上的持股取的是不包含同时持有非流通A股性质的流通股数，
结果可能偏大； 3.指标按报告期展示，新股在上市日的下个报告期才有数据]"""

'266自由流通股(股)': 'freeCirculationStock',

'267受限流通A股(股)': 'limitedCirculationAShares',

'268一般风险准备(金融类)': 'generalRiskPreparation',

'269其他综合收益(利润表)': 'otherComprehensiveIncome',

'270综合收益总额(利润表)': 'totalComprehensiveIncome',

'271归属于母公司股东权益(资产负债表)': 'shareholdersOwnershipOfAParentCompany ',

'272银行机构数(家)(机构持股)': 'bankInstutionNumber',

'273银行持股量(股)(机构持股)': 'bankInstutionShareholding',

'274一般法人机构数(家)(机构持股)': 'corporationNumber',

'275一般法人持股量(股)(机构持股)': 'corporationShareholding',

'276近一年净利润(元)': 'netProfitLastYear'

'277信托机构数(家)(机构持股)': 'trustInstitutionNumber',

'278信托持股量(股)(机构持股)': 'trustInstitutionShareholding',

'279特殊法人机构数(家)(机构持股)': 'specialCorporationNumber',

'280特殊法人持股量(股)(机构持股)': 'specialCorporationShareholding',

'281加权净资产收益率(每股指标)': 'weightedROE',

'282扣非每股收益(单季度财务指标)': 'nonEPSSingle',

'283最近一年营业收入（万元）': 'lastYearOperatingIncome'

'284国家队持股数量（万股)': 'nationalTeamShareholding'

"""#[注：本指标统计包含汇金公司、证金公司、外汇管理局旗下投资平台、国家队基金、国开、养老金以及中科汇通等国家队机构持股数量]"""

'285业绩预告-本期净利润同比增幅下限%': 'PF_theLowerLimitoftheYearonyearGrowthofNetProfitForThePeriod',

"""#[注：指标285至294展示未来一个报告期的数据。例，3月31日至6月29日这段时间内展示的是中报的数据；如果最新的财务报告后面有多个报告期的业绩预告/快报，只能展示最新的财务报告后面的一个报告期的业绩预告/快报]"""

'286业绩预告-本期净利润同比增幅上限%': 'PF_theHigherLimitoftheYearonyearGrowthofNetProfitForThePeriod',

'287业绩快报-归母净利润': 'PE_returningtotheMothersNetProfit',

'288业绩快报-扣非净利润': 'PE_Non-netProfit',

'289业绩快报-总资产': 'PE_TotalAssets',

'290业绩快报-净资产': 'PE_NetAssets',

'291业绩快报-每股收益': 'PE_EPS'

'292业绩快报-摊薄净资产收益率': 'PE_DilutedROA',

'293业绩快报-加权净资产收益率': 'PE_WeightedROE',

'294业绩快报-每股净资产': 'PE_NetAssetsperShare',

'295应付票据及应付账款(资产负债表)': 'BS_NotesPayableandAccountsPayable',

'296应收票据及应收账款(资产负债表)': 'BS_NotesReceivableandAccountsReceivable',

'297递延收益(资产负债表)': 'BS_DeferredIncome',

'298其他综合收益(资产负债表)': 'BS_OtherComprehensiveIncome',

'299其他权益工具(资产负债表)': 'BS_OtherEquityInstruments',

'300其他收益(利润表)': 'IS_OtherIncome',

'301资产处置收益(利润表)': 'IS_AssetDisposalIncome',

'302持续经营净利润(利润表)': 'IS_NetProfitforContinuingOperations',

'303终止经营净利润(利润表)': 'IS_NetProfitforTerminationOperations',

'304研发费用(利润表)': 'IS_R&DExpense',

'305其中:利息费用(利润表-财务费用)': 'IS_InterestExpense',

'306其中:利息收入(利润表-财务费用)': 'IS_InterestIncome',

'307近一年经营活动现金流净额': 'netCashFlowfromOperatingActivitiesinthepastyear'

308近一年归母净利润（万元）:Net profit attributable to the mother in the recent year (RMB million)

309近一年扣非净利润（万元）: Nearly one year net profit after deduction (million yuan)

310近一年现金净流量（万元）: Net cash flow in the past year (million yuan)

311基本每股收益（单季度）:Basic earnings per share (single quarter)

312营业总收入(单季度)(万元):Total operating income (single quarter) (RMB million)

313业绩预告公告日期 :Announcement date of earnings forecast
[注：本指标展示未来一个报告期的数据。例,3月31日至6月29日这段时间内展示的是中报的数据；如果最新的财务报告后面有多个报告期的业绩预告/快报，只能展示最新的财务报告后面的一个报告期的业绩预告/快报的数据；公告日期格式为YYMMDD，例：190101代表2019年1月1日]

314财报公告日期 earnings announcement date

[注：日期格式为YYMMDD,例：190101代表2019年1月1日]


315业绩快报公告日期  Earnings Update Announcement Date

[注：本指标展示未来一个报告期的数据。例,3月31日至6月29日这段时间内展示的是中报的数据；如果最新的财务报告后面有多个报告期的业绩预告/快报，只能展示最新的财务报告后面的一个报告期的业绩预告/快报的数据；公告日期格式为YYMMDD，例：190101代表2019年1月1日]

316近一年投资活动现金流净额(万元) Net cash flow from investing activities in the past year (RMB million)

317业绩预告-本期净利润下限(万元) Forecast of performance

[注：指标317至318展示未来一个报告期的数据。例，3月31日至6月29日这段时间内展示的是中报的数据；如果最新的财务报告后面有多个报告期的业绩预告/快报，只能展示最新的财务报告后面的一个报告期的业绩预告/快报]

318业绩预告-本期净利润上限(万元) Forecast of Results - Current Period Net Income Cap

319营业总收入TTM(万元)319Total Operating Income TTM(million yuan)

320员工总数(人)Total number of employees (people)

321每股企业自由现金流Corporate Free Cash Flow per Share


322每股股东自由现金流Free cash flow per share for shareholders

资产负债表新增指标---


401专项储备(万元) Special reserve (million yuan)

402结算备付金(万元)Settlement provision (million yuan)

403拆出资金(万元) Funds removed (million yuan)

404发放贷款及垫款(万元)(流动资产科目)Loans and advances granted (million yuan) (current assets account)

405衍生金融资产(万元)Derivative financial assets (million yuan)

406应收保费(万元) Premium receivable(million yuan)

407应收分保账款(万元) Sub-insurance receivables (million yuan)

408应收分保合同准备金(万元)Provision for sub-insurance contracts receivable (RMB million)

409买入返售金融资产(万元)Buy-back financial assets (RMB million)

410划分为持有待售的资产(万元)Assets classified as held for sale (RMB million)

411发放贷款及垫款(万元)(非流动资产科目)Loans and advances granted (million yuan) (non-current asset account)

412向中央银行借款(万元)Borrowings from central banks (RMB million)

413吸收存款及同业存放(万元)Absorption of deposits and interbank deposits (RMB million)

414拆入资金(万元)Funds borrowed (RMB million)

415衍生金融负债(万元) Derivative financial liabilities (RMB million)

416卖出回购金融资产款(万元) Sale of repurchase financial assets (RMB million)

417应付手续费及佣金(万元)Fees and commissions payable (RMB million)

418应付分保账款(万元)Payables to sub-insurance accounts (RMB million)

419保险合同准备金(万元)Provision for insurance contracts (RMB million)

420代理买卖证券款(万元) Agency securities trading (RMB million)

421代理承销证券款(万元)Agency underwriting of securities (RMB million)

422划分为持有待售的负债(万元)Liabilities classified as held for sale (million yuan)

423预计负债(万元)Projected liabilities(million yuan)

424递延收益(万元)（流动负债科目，公告此科目的股票较少，大部分公司没有此数据）Deferred income (million yuan) 

425其中:优先股(万元)(非流动负债科目)Deferred incomeOf which:Preferred stock(million yuan)

426永续债(万元)(非流动负债科目)Perpetual bonds (million yuan)

427长期应付职工薪酬(万元)Long-term employee compensation payable(million yuan)

428其中:优先股(万元)(所有者权益科目)Long-term employee compensation payable Of which:Preferred shares(million)(Owner's equity account)

429永续债(万元)(所有者权益科目)Perpetual debentures(million)

430债权投资(万元) Debt investments(million yuan)

431其他债权投资(万元)Other debt investments(million yuan)

432其他权益工具投资(万元)Investment in other equity instruments(million yuan)

433其他非流动金融资产(万元)Other non-current financial assets(million yuan)

434合同负债(万元)Contract liabilities(million yuan)

435合同资产(万元)Contract assets(million yuan)

436其他资产(万元)Other assets(million yuan)

437应收款项融资(万元) Financing of receivables(million yuan)

438使用权资产(万元)Right-of-use assets(million yuan)

439租赁负债(万元)Lease liabilities (million yuan)

利润表新增指标---


501稀释每股收益(元) Diluted earnings per share (yuan)

502营业总收入(万元) Total operating income(yuan)

503汇兑收益(万元) Foreign exchange gain(yuan)

504其中:归属于母公司综合收益(万元)Comprehensive income attributable to parent company(RMB million)

505其中:归属于少数股东综合收益(万元)Comprehensive income attributable to minority shareholders(RMB million)

506利息收入(万元)Interest income(million yuan)

507已赚保费(万元) Premiums earned(RMB million)

508手续费及佣金收入(万元) Fee and commission income(RMB million)

509利息支出(万元)Interest expense(million yuan)

510手续费及佣金支出(万元) Handling and commission expenses(million yuan)

511退保金(万元) Surrender premiums(million yuan)

512赔付支出净额(万元)Net payout expenses (RMB million)

513提取保险合同准备金净额(万元) Net withdrawal of insurance contract reserve (RMB million)

514保单红利支出(万元)Policy dividend expense (RMB million)

515分保费用(万元) Ceding expenses(million yuan)

516其中:非流动资产处置利得(万元)Gain on disposal of non-current assets (RMB million)

517信用减值损失(万元)Credit impairment loss(million yuan)

518净敞口套期收益(万元)Net exposure hedging gain(million yuan)

519营业总成本(万元)Total operating costs(million yuan)

520信用减值损失(万元、2019格式)Credit impairment loss ($ million, 2019 format)

521资产减值损失(万元、2019格式) Impairment loss on assets ($ million, 2019 format)

现金流量表新增指标---

561加:其他原因对现金的影响2(万元)(现金的期末余额科目)Add:Effect of other causes on cash2 ($ million) 

562客户存款和同业存放款项净增加额(万元)Net increase in customer deposits and interbank deposits ($ million)

563向中央银行借款净增加额(万元)Net increase in borrowings from central banks (million yuan)

564向其他金融机构拆入资金净增加额(万元)Net increase in funds borrowed from other financial institutions (RMB million)

565收到原保险合同保费取得的现金(万元)Cash received from premiums on original insurance contracts (RMB million)

566收到再保险业务现金净额(万元)Net cash received from reinsurance business (RMB million)

567保户储金及投资款净增加额(万元)Net increase in policyholders' deposits and investment funds (RMB million)

568处置以公允价值计量且其变动计入当期损益的金融资产净增加额(万元) Net increase in disposal of financial assets at fair value through profit or loss (RMB million)

569收取利息、手续费及佣金的现金(万元) Cash received from interest, fees and commissions (RMB million)

570拆入资金净增加额(万元)Net increase in funds transferred in (RMB million)

571回购业务资金净增加额(万元)Net increase in funds from repo business (RMB million)

572客户贷款及垫款净增加额(万元) Net increase in loans and advances to customers (RMB million)

573存放中央银行和同业款项净增加额(万元)Net increase in deposits with central banks and interbank (RMB million)

574支付原保险合同赔付款项的现金(万元)Cash paid for claims on original insurance contracts (RMB million)

575支付利息、手续费及佣金的现金(万元)Cash paid for interest, fees and commissions (RMB million)

576支付保单红利的现金(万元)Cash paid for policy dividends (RMB million)

577其中:子公司吸收少数股东投资收到的现金(万元)cash received from minority shareholders' investment in subsidiaries (RMB million)

578其中:子公司支付给少数股东的股利、利润(万元)Dividends and profits paid by subsidiaries to minority shareholders(RMB million)

579投资性房地产的折旧及摊销(万元)Depreciation and amortization of investment properties(RMB million)

580信用减值损失(万元)Credit impairment loss(million yuan)

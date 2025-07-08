# sector-alpha-analyzer

1. **Descarga de datos fundamentales** (dividend yield, beta, EPS, etc.) usando `yfinance`
2. **Estimación del retorno esperado** de cada empresa (dividend yield + crecimiento estimado)
3. **Cálculo del retorno esperado por CAPM**, ajustado por sector
4. **Cálculo de alpha teórica**, para detectar empresas potencialmente infravaloradas o sobrevaloradas
5. **Exportación de resultados a Excel**

---

## 🛠️ Requisitos

- Python 3.8+
- `yfinance`
- `pandas`
- `openpyxl` (para exportar a Excel)

# decimaltool
**基础核心四则运算**

  /**
     * 提供（相对）精确的除法运算，当发生除不尽的情况时，精确到
     * 小数点以后10位，以后的数字四舍五入。
     *
     * @param v1 被除数
     * @param v2 除数
     * @param scale 保留scale位小数
     * @return 两个参数的商
     */
decimalCore.div(double v1, double v2, Integer scale)
scale参数默认保留两位小数（可不传）。

   /**
     * 提供精确的加法运算。
     *
     * @param v1 被加数
     * @param v2 加数
     * @return 两个参数的和
     */
decimalCore.add(double v1, double v2)

   /**
      * 提供精确的减法运算。
      *
      * @param v1 被减数
      * @param v2 减数
      * @return 两个参数的差
      */
decimalCore.sub(double v1, double v2)

   /**
       * 提供精确的乘法运算。
       *
       * @param v1 被乘数
       * @param v2 乘数
       * @return 两个参数的积
       */
decimalCore.mul(double v1, double v2)

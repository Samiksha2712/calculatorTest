# calculatorTest
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using AwesomeCalculator;
using NUnit.Framework;


namespace CalcAppTest

{
    [TestFixture]
    class CalcTests
    {
        [Test]
        public void GetAddition_Input3point4and5point6_Returns9point0()
        {
         [Test]
        public void GetMultiplication_Input4point0and6point0_Returns24point0()
        {

            //Arrange
            double number1 = 4.0;
            double number2 = 6.0;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        [Test]
        public void GetMultiplication_Input4point0and6point0_Returns12point0()
        {

            //Arrange
            double number1 = 2;
            double number2 = 6;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        [Test]
        public void GetMultiplication_Input45point0and45point0_Returns2045point0()
        {

            //Arrange
            double number1 = 45;
            double number2 = 45;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        public void GetMultiplication_Input5point0and6point0_Returns30point0()
        {

            //Arrange
            double number1 = 5;
            double number2 = 6;

            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }

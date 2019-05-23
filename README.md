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

            [Test]
        public void GetDivision_Input8point0and4point0_Returns2point0()
        {

            //Arrange
            double number1 = 8;
            double number2 = 4;

            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        [Test]
        public void GetDivision_Input24point0and6point0_Returns4point0()
        {

            //Arrange
            double number1 = 24;
            double number2 = 6;

            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input4point0and4point0_Returns1point0()
        {

            //Arrange
            double number1 = 4;
            double number2 = 4;

            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
    }
}

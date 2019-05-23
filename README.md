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
        public void Getsubtraction_Input9point0and4point0_Returns5point0()
        {

            //Arrange
            double number1 = 9;
            double number2 = 4;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);


        }

        [Test]
        public void Getsubtraction_Input04point10and0point3_Returns5point0()
        {

            //Arrange
            double number1 = 15;
            double number2 = 10.0;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        [Test]
        public void Getsubtraction_Input10point0and09point0_Returns01point00()
        {

            //Arrange
            double number1 = 10;
            double number2 = 09;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }

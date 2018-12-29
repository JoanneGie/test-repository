# Test-Repository
using OpenQA.Selenium;
using OpenQA.Selenium.Chrome;

namespace FirstTest
{
    class Program
    {
        static void Main(string[] args)
        {
            IWebDriver driver = new ChromeDriver();
            driver.Url = "http://www.google.com/";

            driver.Close();


        }
    }
}

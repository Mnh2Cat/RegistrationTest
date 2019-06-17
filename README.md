import org.junit.runner.RunWith;
import org.junit.runners.Suite;

@RunWith(Suite.class)  //指定运行器
@Suite.SuiteClasses({ 
	IsNullTest_1608.class, 
	ValidConfirmTest_1608.class,
	ValidTypeTest_1608.class,
	ValidLengthTest_1608.class})
//指定要测试的类


public class AllTest {
//方法体为空即可
}


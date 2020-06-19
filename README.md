## AppNovo
/*const Tab = createBottomTabNavigator();
const Stack = createStackNavigator();


const icons = {
  Home:{
    name: 'ios-home'
  },
  Sobre:{
    name: 'ios-people'
  },
  Contato:{
    name: 'ios-call'
  }
};

function Tabs(){
  return(
        <Tab.Navigator
          screenOptions={({route}) => ({
            tabBarIcon:({color, size}) => {
              const {name} = icons[route.name];
              return <Icon name={name} color={color} size={size} />
            }
          }) }
          tabBarOptions={{
            style:{
              backgroundColor: '#121212'
            },
            activeTintColor: 'green'
          }}
          >
            <Tab.Screen name="Home" component={Home} />
            <Tab.Screen name="Sobre" component={Sobre} />
        </Tab.Navigator>
        
      );
}

export default function App(){
  return(
    <NavigationContainer>
      <Stack.Navigator>
        <Stack.Screen name="Home" component={Tabs} options={{headerShown:false}} />
        <Stack.Screen name="Contato" component={Contato} />
      </Stack.Navigator>
    </NavigationContainer>
  );
}*/
# 图片查看器，支持手势缩放、分享

# 安装
> npm install react-native-sf-image-zoom-viewer

# 例子
'''
import SFZoomView from 'react-native-sf-image-zoom-viewer';
export default class App extends React.Component {
  show=()=>{
    
  }
  render(){
    return(
      <View style={{flex:1,}}>
        ...
        ...
        <SFZoomView ref={(ref)=>{this.zoomViewer = ref}}/>
      </View>
    )
  }
}

'''

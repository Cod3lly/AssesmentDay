const textElement = document.getElementById('text')
const optionButtonsElement = document.getElementById('option-buttons')

let state = {}

function startGame() {
  state = {},
  showTextNode(1)
}



function showTextNode(textNodeIndex) {
  const textNode = textNodes.find(textNode => textNode.id === textNodeIndex)
  textElement.innerText = textNode.text
  while (optionButtonsElement.firstChild) {
    optionButtonsElement.removeChild(optionButtonsElement.firstChild)
  }

  textNode.options.forEach(option => {
    if (showOption(option)) {
      const button = document.createElement('button')
      button.innerText = option.text
      button.classList.add('transition', 'ease-in-out', 'delay-110', 'p-5', 'm-2', 'bg-yellow-400', 'text-black', 'border-4', 'border-black', 'hover:bg-yellow-500')
      button.addEventListener('click', () => selectOption(option))
      optionButtonsElement.appendChild(button)
    }
  })
}

function showOption(option) {
  return option.requiredState == null || option.requiredState(state)
}

function selectOption(option) {
  const nextTextNodeId = option.nextText
  if (nextTextNodeId <= 0) {
    return startGame()
  }
  state = Object.assign(state, option.setState)
  showTextNode(nextTextNodeId)
}

const textNodes = [
  {
    id: 1,
    text: 'Bunny is a lovely rabbit with colourful dreams. Her biggest dream is to travel the world \n \n Her journey starts with \:',
    options: [
      {
        text: 'Living in a hole with her family.',
        setState: { journey: true},
        nextText: 2
      },
      {
        text: 'Living in a cage.',
        setState: { journey: true},
        nextText: 3
      },
      {
        text: 'On a table at the butcher.',
        setState: { journey: true},
        nextText: 4
      }
    ]
  },
  {
    id: 2,
    text: 'On an overcast rainy day\:',
    options: [
      {
        text: 'She gets thrown out by her parents.',
        requiredState: (currentState) => currentState.journey,
        setState: { journey: true },
        nextText: 5
      },
      {
        text: 'Wants to move out.',
        requiredState: (currentState) => currentState.journey,
        setState: { journey: true},
        nextText: 5
      },
    ]
  },
  {
    id: 3,
    text: 'On an overcast rainy day\:',
    options: [
        {
            text: 'She picks the lock.',
            requiredState: (currentState) => currentState.journey,
            setState: { journey: true },
            nextText: 5  
          },
          {
            text: 'Waits for the door to open.',
            requiredState: (currentState) => currentState.journey,
            setState: { journey: true },
            nextText: 5
          },
          {
            text: 'Prefers sitting in the cage.',
            requiredState: (currentState) => currentState.journey,
            setState: { journey: true },
            nextText: 1
          },
    ]
  },
  {
    id: 4,
    text: 'On an overcast rainy day\:',
    options: [
      {
        text: 'She runs away.',
        requiredState: (currentState) => currentState.journey,
        setState: { journey: true},
        nextText: 5
      },
      {
        text: 'She gets butchered',
        requiredState: (currentState) => currentState.journey,
        setState: { journey: true},
        nextText: 1
      },
    ]
  },
  {
    id: 5,
    text: 'Her adventures start with\:',
    options: [
      {
        text: 'Reaching the forest.',
        requiredState: (currentState) => currentState.journey,
        nextText: 6
      },
      {
        text: 'Meeting a big bad wolf.',
        requiredState: (currentState) => currentState.journey,
        nextText: 7
      },
      {
        text: 'Living outside her hole.',
        requiredState: (currentState) => currentState.journey,
        nextText: 1
      },
    ]
  },

  {
    id: 6,
    text: 'Oh what a beautiful forest!!',
    options: [
      {
        text: 'She eats a magical fruit which allows her to fly.',
        nextText: 8
      },
      {
        text: 'She gets scared.',
        nextText: 1
      },
    ]
  },
  {
    id: 7,
    text: 'Ahhhhhhh! ',
    options: [
      {
        text: 'She flirts with the wolf',
        nextText: 9
      },
      {
        text: 'She gets eaten by the wolf',
        nextText: 1
      },
    ]
  },
  {
    id: 8,
    text: 'OMG!!! I can fly!!! Here I come world!!',
  },
  {
    id: 9,
    text: 'She falls in love with the wolf and has bunny wolf babies',
  },
]
startGame()